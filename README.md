# words-per-min-calculator-
[3/6, 11:18 PM] Mousami: root {
    --font: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    --black: #000000;
    --white: #d0d0d0;
    --light-gray: #898b8f;
    --dark-gray: #535353;
    --lime: #99f849;
    --green: #6aff98;
    --red: #ff5932;
    --yellow: #efd81c;
}
[3/6, 11:18 PM] Mousami: {
    box-sizing: border-box;
    font-family: var(--font);
}
[3/6, 11:18 PM] Mousami: body {
    background-color: var(--black);
    margin: 0;
}
[3/6, 11:19 PM] Mousami: container {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}
[3/6, 11:19 PM] Mousami: timer {
    position: absolute;
    top: 4rem;
    font-size: 3rem;
    color: var(--yellow);
    font-weight: bold;
}
[3/6, 11:19 PM] Mousami: .quote {
    background-color: var(--black);
    color: var(--light-gray);
    padding: 1rem;
    border-radius: 0.5rem;
    width: 700px;
    max-width: 90%;
}
[3/6, 11:19 PM] Mousami: quote-display {
    margin-bottom: 1rem;
    margin-left: calc(1rem + 2px);
    margin-right: calc(1rem + 2px);
}
[3/6, 11:20 PM] Mousami: quote-input {
    background-color: transparent;
    color: var(--dark-gray);
    border: none;
    outline: none;
    width: 100%;
    height: 8rem;
    margin: auto;
    resize: none;
    padding: 0.5rem 1rem;
}
[3/6, 11:20 PM] Mousami: .text {
    font-size: 1.5rem;
    text-align: left;
}
[3/6, 11:20 PM] Mousami: ::placeholder {
    color: var(--dark-gray);
}
[3/6, 11:20 PM] Mousami: correct {
    color: var(--dark-gray);
}
[3/6, 11:21 PM] Mousami: incorrect {
    color: var(--red);
    text-decoration: underline;
}
[3/6, 11:22 PM] Mousami: statistics {
    position: absolute;
    min-width: 80%;
    bottom: 8rem;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-evenly;
    align-content: space-evenly;
    flex-flow: row wrap;
    row-gap: 2rem;
}
[3/6, 11:22 PM] Mousami: round-statistics,
.global-statistics {
    display: flex;
    flex-direction: column;
    visibility: hidden;
}
[3/6, 11:22 PM] Mousami: statistics-title {
    color: var(--yellow);
    font-size: 1.5rem;
    margin-bottom: 1rem;
}
[3/6, 11:22 PM] Mousami: blink {
    animation: blinker 1s linear infinite;
}
[3/6, 11:23 PM] Mousami: @keyframes blinker {
    50% {
        opacity: 0;
    }
}
[3/6, 11:21 PM] Mousami: loading {
    display: flex;
    justify-content: center;
    align-items: center;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 99;
    background-color: var(--black);
    color: var(--yellow);
    font-family: var(--font);
    font-size: 2rem;
}
[3/6, 11:21 PM] Mousami: all-time-high {
    visibility: hidden;
    display: inline-block;
    background-color: var(--yellow);
    border-radius: 0.5rem;
    margin-left: 10px;
    padding: 2px 5px;
    font-size: 0.7rem;
    font-weight: bold;
}
