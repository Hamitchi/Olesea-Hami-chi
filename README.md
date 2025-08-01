<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Invitație Nuntă Renat & Olesea</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display&family=Roboto&display=swap');
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      background-color: #f9f9f9;
      font-family: 'Roboto', sans-serif;
      color: #444;
      line-height: 1.6;
      display: flex;
      justify-content: center;
      padding: 20px;
    }
    .container {
      max-width: 600px;
      background: #fff;
      padding: 40px 30px;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }
    h1, h2 {
      font-family: 'Playfair Display', serif;
      color: #2f2f2f;
      margin-bottom: 20px;
      text-align: center;
    }
    h1 { font-size: 2.8rem; margin-bottom: 10px; }
    h2 { font-size: 1.8rem; margin-top: 40px; }
    p {
      font-size: 1rem;
      margin-bottom: 12px;
      color: #555;
      text-align: center;
    }
    .highlight { color: #b77a56; font-weight: 600; }
    .location-details {
      background: #f4f4f4;
      padding: 20px;
      border-radius: 8px;
      margin-top: 15px;
      font-size: 1rem;
      text-align: center;
      color: #333;
    }
    .program, .dresscode {
      margin-top: 30px;
      font-size: 1rem;
      color: #444;
    }
    form {
      margin-top: 40px;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    label {
      font-weight: 600;
      font-size: 1rem;
      color: #2f2f2f;
    }
    input, select {
      padding: 10px;
      border: 1.5px solid #ccc;
      border-radius: 6px;
      font-size: 1rem;
      transition: border-color 0.3s ease;
    }
    input:focus, select:focus {
      border-color: #b77a56;
      outline: none;
    }
    button {
      background-color: #b77a56;
      color: white;
      padding: 12px;
      border: none;
      border-radius: 8px;
      font-size: 1.1rem;
      cursor: pointer;
      transition: background-color 0.3s ease;
      font-family: 'Playfair Display', serif;
    }
    button:hover {
      background-color: #a16544;
    }
    footer {
      margin-top: 40px;
      text-align: center;
      font-size: 0.9rem;
      color: #aaa;
    }
    @media (max-width: 650px) {
      .container { padding: 30px 20px; max-width: 90vw; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Renat & Olesea</h1>
    <p class="highlight">Vă invită să sărbătoriți împreună Ziua Nunții lor</p>
    <p>8 mai 2026, ora 16:00</p>

    <h2>Locația</h2>
    <div class="location-details">
      <strong>Restaurant:</strong> Lago Event Park<br />
      <strong>Sala:</strong> Sicilia<br />
      <strong>Pe malul lacului Dănceni, la numai 12 km de orașul Chișinău</strong><br />
      <strong>Adresă:</strong> Dănceni-R3, sat Socițeni, raionul Ialoveni, Republica Moldova
    </div>

    <h2>Program</h2>
    <p class="program">
      16:00 - Sosirea invitaților<br />
      16:30 - Ceremonia și toastul<br />
      17:00 - Cina festivă și petrecerea
    </p>

    <h2>Dress Code</h2>
    <p class="dresscode">Elegant minimalist – nuanțe de alb, gri metalic și accente calde</p>

    <h2>Confirmare Participare</h2>
    <form 
      action="https://docs.google.com/forms/d/e/1FAIpQLSc9eD3iD4mPntJhA9h8T-KlQ5Fh19rxXIlpXtX-WA2Mu-vocQ/formResponse" 
      method="POST" target="_blank" 
      id="rsvpForm">
      
      <label for="name">Nume complet:</label>
      <input type="text" id="name" name="entry.1822092675" required />

      <label for="email">Email:</label>
      <input type="email" id="email" name="entry.2114069448" required />

      <label for="guests">Număr persoane:</label>
      <select id="guests" name="entry.897349252" required>
        <option value="">Selectați</option>
        <option value="1">1</option>
        <option value="2">2</option>
        <option value="3">3</option>
        <option value="4+">4 sau mai multe</option>
      </select>

      <button type="submit">Trimite</button>
    </form>

    <footer>
      Vă mulțumim că veți fi alături de noi în această zi specială!
    </footer>
  </div>
</body>
</html>
