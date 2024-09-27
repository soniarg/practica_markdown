# práctica_markdown
# TENDA

## BEAUTY STORE

**Propietària:** *Sonia Roig Marti*  
`Correu: beautystore@gmail.com`  

La belleza se describe comúnmente como una cualidad de los entes que hace que estas sean placenteros de percibir. Tales entes pueden incluir paisajes, atardeceres o amaneceres, cielos nocturnos, personas, animales, plantas, obras de arte, etc. Belleza es una noción abstracta ligada a numerosos aspectos de la existencia humana. La belleza se estudia dentro de la disciplina filosófica de la estética, además de otras disciplinas como la historia, la sociología y la psicología social.  

> La belleza no hace feliz al que la posee, sino a quien puede amarla. (Hermann Hesse)

Els nostres productes en format JSON:
```json
{
  "Tenda": 
  {
    "Nom": "BEAUTYSTORE",
    "Productes": 
    [
      {
        "Nom producte": "Perfum",
          "Marca": "Dior",
          "Preu": 9.99,
          "En stock": true,
          "Característiques": 
          {
            "Durabilidad": "6 hores",
            "Olor": 
            [
                "roses",
                "agua del mar",
                "girasols"

            ],
            "Garantia": null
          }
        },
        {
          "Nom producte": "Champu",
          "Marca": "NVIDIA",
          "Preu": 4.55,
          "En stock": false,
          "Característiques": 
          {
            "Durabilidad": "10 hores",
            "olor":
            [
               "roses",
               "golosines"
            ]
          }
        },
        {
          "Nom producte": "Pintallavis",
          "Marca": "Dior",
          "Preu": 125.60,
          "En stock": true,
          "Característiques": {
            "Stock": 10,
            "colors":
            [
              "roig",
              "rosa",
              "roig fosc"
            ]
          }
        }
    ],
      "Contacte": {
        "Email": "info@beautystore.com",
        "Telèfons": [
          "9988664422",
          "1234567890"
        ]
      }
  }
}
```  
Els nostres productes en format YAML:
```yaml
---
Tenda: 
  Nom: "BEAUTYSTORE"
  Productes: 
   - Nom producte: "Perfum"
    Marca: "Dior"
    Preu: "9.99"
    En stock: "true"
    Característiques: 
      Durabilidad: "6 hores"
      Olor: 
      - "roses"
      - "agua del mar"
      - "girasols"
      Garantia: 
    - Nom producte: "Champu"
    Marca: "NVIDIA"
    Preu: "4.55"
    En stock: "false"
    Característiques: 
      Durabilidad: "10 hores"
      olor: 
      - "roses"
      - "golosines"
    - Nom producte: "Pintallavis"
    Marca: "Dior"
    Preu: "125.6"
    En stock: "true"
    Característiques: 
      Stock: "10"
      colors: 
      - "roig"
      - "rosa"
      - "roig fosc"
  Contacte: 
    Email: "info@beautystore.com"
    Telèfons: 
    - "9988664422"
    - "1234567890"  
```
[Enlace página web (click aquí)]( https://www.thebeautystore.com/?srsltid=AfmBOoryY1rFcc3xi5UFiyz_Lz4idPT9zJuSjk-Seqs601pZLtIUu1Qe)  

![Imágen de nuestro logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKGrzlpxQin2NEAlMphv3kYsithl_usycGkw&s)  

* Contacte  
  * Telèfon: 1234567890
  * Correu: beautystore@gmail.com
