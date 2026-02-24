---
layout: default
title: Bestellen
permalink: /bestellen/
---
<section class="container contact-page">
  <h1>Bestel via dit formulier</h1>
  <p>Voor vragen of samenwerkingen neem contact op met eindelooslicht@antrum-technologies.nl</p>

  <form action="https://api.staticforms.xyz/submit" method="POST" class="contact-form">
    <input type="hidden" name="apiKey" value="{{ site.static_form_api_key }}">
    <input type="hidden" name="redirectTo" value="https://eindelooslicht.nl/bedankt">

    <label for="voornaam" class="form-label">Voornaam
    <input type="text" class="form-control" id="voornaam" name="voornaam" required>
    </label>
        
    <label for="achternaam" class="form-label">Achternaam
    <input type="text" class="form-control" id="achternaam" name="achternaam" required>
    </label>

    <label for="email" class="form-label">Emailadres
    <input type="text" class="form-control" id="email" name="email" required>
    </label>

    <label for="straat" class="form-label">Straat
    <input type="text" class="form-control" id="straat" name="straat" required>
    </label>

    <label for="huisnummer" class="form-label">Huisnummer
    <input type="text" class="form-control" id="huisnummer" name="huisnummer" required>
    </label>

    <label for="postcode" class="form-label">Postcode
    <input type="text" class="form-control" id="postcode" name="postcode" required>
    </label>

    <label for="plaats" class="form-label">Plaats
    <input type="text" class="form-control" id="plaats" name="plaats" required>
    </label>

    <label for="land" class="form-label">Land
    <input type="text" class="form-control" id="land" name="land" value="Nederland" disabled>
    <small>We verzenden momenteel alleen binnen Nederland. Neem contact met ons op voor de mogelijkheden.</small>
    </label>

    <fieldset>
      <legend class="col-form-label pt-0">Kies je lamp</legend>
      <div class="form-check">
        <input class="form-check-input" type="checkbox" name="lampenkap" id="model1" value="Lichtgedraaid - Tafellamp - Maat S">
        <label class="form-check-label" for="model1">Lichtgedraaid - Tafellamp - Maat S - Donkere voet - 69 EUR</label>
      </div>
      <div class="form-check">
        <input class="form-check-input" type="checkbox" name="lampenkap" id="model2" value="Lichtgedraaid - Tafellamp - Maat M">
        <label class="form-check-label" for="model2">Lichtgedraaid - Tafellamp - Maat M - Donkere voet - 74 EUR</label>
      </div>
      <div class="form-check">
        <input class="form-check-input" type="checkbox" name="lampenkap" id="model3" value="Lichtgedraaid - Tafellamp - Maat L">
        <label class="form-check-label" for="model3">Lichtgedraaid - Tafellamp - Maat L - Donkere voet - 79 EUR</label>
      </div>
      <div class="form-check">
        <input class="form-check-input" type="checkbox" name="lampenkap" id="model1" value="Lichtgedraaid - Tafellamp - Maat S">
        <label class="form-check-label" for="model1">Lichtgedraaid - Tafellamp - Maat S - Lichte voet - 69 EUR</label>
      </div>
      <div class="form-check">
        <input class="form-check-input" type="checkbox" name="lampenkap" id="model2" value="Lichtgedraaid - Tafellamp - Maat M">
        <label class="form-check-label" for="model2">Lichtgedraaid - Tafellamp - Maat M - Lichte voet - 74 EUR</label>
      </div>
      <div class="form-check">
        <input class="form-check-input" type="checkbox" name="lampenkap" id="model3" value="Lichtgedraaid - Tafellamp - Maat L">
        <label class="form-check-label" for="model3">Lichtgedraaid - Tafellamp - Maat L - Lichte voet - 79 EUR</label>
      </div>
      <div class="form-check">
        <input class="form-check-input" type="checkbox" name="lampenkap" id="model4" value="Lichtgedraaid - Hanglamp">
        <label class="form-check-label" for="model4">Lichtgedraaid - Hanglamp - 59 EUR</label>
      </div>
    </fieldset>

    <fieldset>
      <legend class="col-form-label pt-0">Verzendmethode</legend>
      <div class="form-check">
        <input class="form-check-input" type="radio" name="verzendmethode" id="afhalen" value="Ophalen gratis" required>
        <label class="form-check-label" for="afhalen">Afhalen in Utrecht of Heeze (gratis)</label>
        <small>We nemen contact met je op om een afhaalmoment in te plannen.</small>
      </div>
      <div class="form-check">
        <input class="form-check-input" type="radio" name="verzendmethode" id="verzenden" value="Verzenden 5 euro">
        <label class="form-check-label" for="verzenden">Verzenden (€ 6,-)</label>
        <small>Via PostNL met track & trace.</small>
      </div>
    </fieldset>

    <button type="submit" class="btn btn-primary w-100">Ik ga bestellen!</button>
  </form>
</section>
