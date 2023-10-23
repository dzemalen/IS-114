#definerer alle variablene til flagget
red = rectangle(352, 256, "solid", "red")
blueh = rectangle(352, 32, "solid", "darkblue")
bluev = rectangle(32, 256, "solid", "darkblue")
whiteh = rectangle(352, 64, "solid", "white")
whitev = rectangle(64, 256, "solid", "white")

#skriver nå verdiene i riktig rekkefølge slik at den rette fargen kommer først
norway =
  put-image(blueh,176 ,128,
    put-image(bluev, 128, 128,
      put-image(whiteh, 176, 128,
        put-image(whitev, 128, 128,
          red))))
#skirver ut bilde
norway

