### Hola Soy Kenya  👋 Bienvenido(a)

...js

const thai = {
  pronouns: "she" | "her",
  code: [ HTML, CSS,  Python, Jquery],
  tools: [, Jquery , Bootstrap , Django ]
  Base Date: { sqlpostres },
 challenge: "Hago lindas Webs"
}
...

Algunas frases autorefrenciales :

🌱 siempre se me ocurren cosas muy buenas ...

👯 Amo el trabajo en equipo ..

🤔 Me estas leyendo ahora, te quiero robar una sonrisa .

😄 Pronouns: kreutzenia .

💡 Creando nuevos retos .

🗂️ Tengo más repo.... hay que buscar ...

♐ Me gusta codificar 

📰 Mi reciente repositorio - Manejo de Crud 

🏆 Quisiera muchas medallas ...

🎩 Si me invitas un café te enseño..  pero te advierto que estoy aprendiendo . 

💬 Soy sociable 

💭 GitHub una  gran comunidad  que me envuelve .

👨‍💻 Mi estado actual .... coding.

Sí soy genial ...y Tú tambien.


package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                    "A kind of metalHead-melomaniac-gearAddict-amateurMusician-traveler-foodLover-gamer-coder-programmer-catLover-sportsAficionado hybrid",
		"- 🔭 I’m currently working on":      "Tredicom as a Senior Software Developer --- UAdeC as a Part Time Teacher",
		"- 🌱 I’m currently learning":        "Golang, MongoDB, RabbitMQ, K8s, GCP (Tech stack from my company) --- Sharpening my Front End Skills for the MERN stack (Personal goal)",
		"- 👯 I’m looking to collaborate on": "Python, Golang and Docker related projects",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 💬 Ask me about":                  "Python, PHP, Laravel, SQL, Software Design & Architecture, Web-Dev and SEO",
		"- 📫 How to reach me:":              "https://github.com/AnhellO#you-can-reach-me-at-alien",
	}
}

