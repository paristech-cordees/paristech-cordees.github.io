## Liens de connexion - groupe 1

Veuillez sélectionner votre salle.

- <a id="one" class="button" href='https://fr.lmgtfy.app/?q=green&iie=0' target='_blank'>10h - 10h30</a>
- <a id="two" class="button" href='https://fr.lmgtfy.app/?q=blue&iie=0' target='_blank'>11h - 11h30</a>

- <a class="button" href='' target='_blank'>Aide</a>

<script>
    var d = new Date();
var currHour = d.getHours();
if (currHour >= 9 && currHour <= 12) {
    document.getElementById("one").style.fontSize = "16";
} else if (currHour > 12 && currHour < 20) {
    document.getElementById("two").style.fontSize = "16";
}
</script>