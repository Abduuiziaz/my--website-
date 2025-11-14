body {
    font-family: sans-serif;
    text-align: center;
    margin: 0;
    padding: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
}

h1 {
    color: #6a0dad;
    font-size: 32px;
    margin: 20px 0;
}

p {
    font-size: 20px;
    margin: 15px 0;
}

h2 {
    font-size: 28px;
    margin-top: 40px;
}

textarea {
    width: 90%;
    max-width: 500px;
    padding: 15px;
    font-size: 18px;
    font-family: sans-serif;
    border: 2px solid #6a0dad;
    border-radius: 5px;
    margin-top: 20px;
}

button {
    background-color: #6a0dad;
    color: white;
    padding: 15px 40px;
    font-size: 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 15px;
}

button:hover {
    background-color: #5a0c9d;
}

#thankYou {
    color: #6a0dad;
    font-size: 24px;
    font-weight: bold;
    margin-top: 20px;
}

@media (max-width: 600px) {
    h1 {
        font-size: 28px;
    }
    
    h2 {
        font-size: 24px;
    }
    
    p {
        font-size: 18px;
    }
}
