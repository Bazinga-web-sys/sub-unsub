<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Unsubscribe</title>
    <link rel="icon" type="image/png" href="assets/favicon-96x96.png" sizes="96x96" />
    <link rel="icon" type="image/svg+xml" href="assets/favicon.svg" />
    <link rel="shortcut icon" href="assets/favicon.ico" />
    <link rel="apple-touch-icon" sizes="180x180" href="assets/apple-touch-icon.png" />
    <link rel="manifest" href="assets/site.webmanifest" />
    <link rel="stylesheet" href="css/styles.css" />
</head>

<body>
    <main class="card">
        <div class="spacer-top"></div>

        <img src="assets/logo.svg" alt="Logo_firme" class="logo" />

        <div class="spacer-after-logo"></div>

        <h1>Unsubscribe from <br> Survey Invites</h1>

        <div class="spacer-after-title"></div>

        <p class="question">Would you like to unsubscribe from <br>receiving survey invites from <br> <b>{Account}</b>?
        </p>

        <div class="spacer-before-actions"></div>

        <div class="actions">
            <button class="btn unsub">Yes, Unsubscribe</button>
            <a href="stay.html" class="btn-link">No, Keep Me Subscribed</a>
        </div>

        <div class="spacer-before-footer"></div>

        <footer>
            <p>This service is provided by <strong>InsiderCX</strong> to enhance <br> your appointment experience.</p>
            <p class="copyright">© 2024 <strong>InsiderCX</strong>. All rights reserved.</p>
        </footer>
    </main>
</body>

</html>


<style>
    @import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;600&family=Montserrat:wght@600&display=swap");

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html,
body {
  height: 100%;
}

body {
  font-family: "Inter", sans-serif;
}

.card {
  background: linear-gradient(to bottom, #ffffff, #fdf8e9);
  min-height: 100vh;
  width: 100vw;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 1.5rem;
}

.spacer-top {
  flex: 1;
  min-height: 1rem;
}

.logo {
  width: 15rem;
  height: 5.5rem;
  flex-shrink: 0;
  margin: 0 auto;
  display: block;
}

.spacer-after-logo {
  flex: 1.5;
  min-height: 2rem;
}

h1 {
  font-family: "Montserrat", sans-serif;
  font-size: 1.5rem;
  font-weight: 700;
  color: #201a02;
  flex-shrink: 0;
  margin-bottom: 1rem;
}

.content {
  flex-shrink: 0;
}

.spacer-after-title {
  flex: 0.5;
  min-height: 0.5rem;
}

p {
  font-size: 0.95rem;
  line-height: 1.5;
  margin-bottom: 1rem;
  color: #4b5563;
  font-weight: 400;
}

p.question {
  font-size: 0.95rem;
  line-height: 1.5;
  color: #4b5563;
  font-weight: 400;
  flex-shrink: 0;
}

.spacer-before-actions {
  flex: 2;
  min-height: 2rem;
}

.actions {
  flex-shrink: 0;
}

.btn {
  display: block;
  width: 100%;
  padding: 1rem;
  border: none;
  border-radius: 5px;
  font-weight: 700;
  cursor: pointer;
  margin-bottom: 1rem;
  transition: opacity 0.2s, box-shadow 0.2s;
}

.btn.unsub {
  background: #fbcc18;
  color: #000;
}

.btn.unsub:hover,
.btn.unsub:focus,
.btn.unsub:active {
  opacity: 0.9;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.btn-link {
  display: inline-block;
  font-size: 0.95rem;
  color: #1a1a1a;
  text-decoration: none;
  cursor: pointer;
  font-weight: 700;
}

.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  opacity: 0.7;
}

.spacer-before-footer {
  flex: 1.5;
  min-height: 1.5rem;
}

footer {
  font-size: 0.7rem;
  color: #4b5563;
  font-weight: 400;
  line-height: 1.4;
  text-align: center;
  flex-shrink: 0;
}

footer strong {
  font-weight: 700;
}
footer > p {
  font-size: small;
}
footer .copyright {
  margin-top: 0.5rem;
  font-size: 0.7rem;
  color: #4b5563;
}

/* Desktop responsive */
@media (min-width: 768px) {
  .card {
    max-width: 480px;
    min-height: 100vh;
    margin: 0 auto;
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
  }

  h1 {
    font-size: 1.5rem;
  }
}

</style>


