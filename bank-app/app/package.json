const express = require("express");

const app = express();

const PORT = 3000;

app.get("/", (req, res) => {
    res.send(`
        <h1>🏦 Bank Application</h1>
        <h2>Version : V1</h2>
        <p>Running on Amazon EKS</p>
    `);
});

app.get("/health", (req, res) => {
    res.status(200).send("OK");
});

app.listen(PORT, () => {
    console.log(`Bank App running on port ${PORT}`);
});
