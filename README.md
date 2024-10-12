body {
    font-family: 'Arial', sans-serif;
    background-color: #f3f4f6;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    overflow: hidden;
}

.container {
    text-align: center;
    background-color: #fff;
    padding: 40px;
    border-radius: 10px;
    box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.1);
    position: relative;
}

h1 {
    color: #ff4081;
    font-size: 2.5rem;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    color: #fff;
    background-color: #ff4081;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

button:hover {
    background-color: #ff6385;
}

#wish {
    margin-bottom: 20px;
    font-size: 18px;
}

#birthdayMessage {
    margin-top: 20px;
    font-size: 24px;
    font-weight: bold;
    color: #4caf50;
    animation: fadeIn 2s ease;
}

.hidden {
    display: none;
}

@keyframes fadeIn {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
}

#confetti {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    pointer-events: none;
    z-index: -1;
}
