---
layout: splash # archive
permalink: /
title: "Papy vend sa collec'"
excerpt: Just the cars we love

header:
  #overlay_color: "#333"
  overlay_image: /assets/images/banner-delahaye-type-235-235m-breitling.jpg
  actions:
     - label: "More"
       url: "/vso/"
     - label: "About"
       url: "/about/"

feature_row:
  - image_path: /assets/images/cartoon-car.gif
    title: "En 2021, Papy vend sa collec'"
    excerpt: "En 2021, la collection de véhicules français d'avant-guerre de JWA Classic sera mise en vente progressivemment via notre site, sur la base d'un système d'enchères originales. "
    url: "/vso"
    btn_label: "En savoir plus"
    btn_class: "btn--inverse"


feature_row2:
  - image_path: /assets/images/joel-winter-portrait-hp.jpg
    title: "Ma démarche : ensemble, prenons le temps de faire une bonne affaire !'"
    excerpt: "Spécialisé dans la restauration et l’histoire de **véhicules français d’avant-guerre**, je souhaite aujourd’hui céder une partie de ma collection.
    J’ai donc essayé d’imaginer un processus de ventes aux enchères, mais en plus sympa,  pour céder progressivement mes voitures **à un prix équitable** et tout en profitant du **plaisir de rencontrer d’autres collectionneurs**."
    url: "/vso"
    btn_label: "En savoir plus"
    btn_class: "btn--inverse"

feature_row3:
  - image_path: /assets/images/marteau-enchères-hp.jpg
    title: "Les petites ventes aux enchères JWA Classic : une mise aux enchères, mais en plus sympa et équitable"
    excerpt: "Pour chaque véhicule : une période dédiée à la présentation détaillée du véhicule suivie d'une mise aux enchères, sans prix de réserve ni frais additionnel pour l'acheteur.
    L'objectif étant de réaliser une vente équitable, pour l'acheteur comme pour le vendeur, en toute transparence à chaque étape de la transaction. Envie d'en savoir plus ? "
    url: "/vso"
    btn_label: "En savoir plus"
    btn_class: "btn--inverse"

feature_row_inscription:
  - image_path: /assets/images/jolie-photo.jpg
    title: "Formulaire d'inscription"
    excerpt: |
      L'email sera envoye sur contact@jwaclassic.com <br/>
      Les champs peuvent etre modifies et codifies <br/>
      <form action="https://formspree.io/f/mqkgdgww" method="POST">
        <label>
          Your email:
          <input type="text" name="_replyto">
        </label>
        <label>
          Your message:
          <textarea name="message"></textarea>
        </label>
        <button type="submit">Send</button>
      </form>
    # url: "/about"
    # btn_label: "S'inscrire"
    # btn_class: "btn--primary"
---

{% include feature_row id="feature_row" type="left" %}
{% include feature_row id="feature_row2" type="right" %}
{% include feature_row id="feature_row3" type="left" %}
{% include feature_row id="feature_row_inscription" type="center" %}
