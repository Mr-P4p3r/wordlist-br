# wordlist-br

> Uma wordlist brasileira para pentesters — Brazilian wordlist for pentesters.

---

## 🇧🇷 Português

Essa wordlist foi criada há cerca de 2 anos, buscando atender a nossa necessidade de uma lista para pentesters focada em palavras do Brasil. Com o tempo, ela foi crescendo e recebendo novas categorias para cobrir cada vez mais o contexto cultural, social e corporativo brasileiro.

### Conteúdo

| Qtd | Descrição |
|----:|-----------|
| 7.777 | Palavras gerais |
| 5.566 | Cidades |
| 1.993 | Nomes masculinos mais populares |
| 1.400 | Nomes femininos mais populares |
| 928 | Nomes de bandas |
| 677 | Times de futebol |
| 91 | Gírias e palavrões |
| 232 | Protagonistas de novelas das 20h e 21h |
| 50 | Santos e expressões religiosas |
| 23 | Top times de E-Sports globais |
| 83 | Top empresas, bancos e startups brasileiras |
| 51 | Top times de basquete globais |
| 43 | Senhas mais utilizadas no Brasil |
| 146.645 | Números |

**Total: 165.400**

### Novidades

- **Gírias e palavrões** — termos do cotidiano informal brasileiro, muito comuns como senhas fracas.
- **Protagonistas de novelas das 20h e 21h** — nomes de personagens icônicos da televisão brasileira.
- **Santos e expressões religiosas** — santos católicos, expressões de fé e devoção popular.
- **Top times de E-Sports globais** — organizações e clubes de esports com grande presença no Brasil.
- **Top empresas, bancos e startups brasileiras** — marcas e instituições amplamente conhecidas no país.
- **Top times de basquete globais** — franquias da NBA e ligas europeias com relevância no cenário brasileiro.

Diversas palavras únicas dessas categorias foram incorporadas à lista principal `MrP4p3r`, com deduplicação e reordenação completas.

---

## 🇺🇸 English

This wordlist was created about 2 years ago to meet our need for a penetration testing word list focused on Brazilian context. Over time it has grown with new categories to cover the cultural, social and corporate landscape of Brazil more thoroughly.

### Contents

| Count | Description |
|------:|-------------|
| 7,777 | General words |
| 5,566 | Cities |
| 1,993 | Most popular male names |
| 1,400 | Most popular female names |
| 928 | Music bands |
| 677 | Soccer teams |
| 91 | Brazilian slang and profanity |
| 232 | Main characters from prime-time soap operas (8 PM & 9 PM) |
| 50 | Saints and religious expressions |
| 23 | Top global E-Sports teams |
| 83 | Top Brazilian companies, banks and startups |
| 51 | Top global basketball teams |
| 43 | Most used passwords in Brazil |
| 146,645 | Numbers |

**Total: 165,400**

### What's new

- **Brazilian slang & profanity** — informal everyday terms widely used as weak passwords.
- **Prime-time soap opera characters** — iconic character names from Brazilian TV (Globo 8 PM & 9 PM slots).
- **Saints & religious expressions** — Catholic saints, popular faith expressions and devotional terms.
- **Top global E-Sports teams** — organizations with a strong following in Brazil's gaming scene.
- **Top Brazilian companies, banks & startups** — well-known brands and financial institutions across the country.
- **Top global basketball teams** — NBA franchises and European league clubs relevant to the Brazilian audience.

All new category words have been merged into the main `MrP4p3r` list with full deduplication and alphabetical sorting applied.

---

## Usage

```bash
# Clone the repository
git clone https://github.com/MrP4p3r/wordlist-br.git

# Use with your favourite tool
hydra -l admin -P wordlist-br/MrP4p3r <target> http-post-form "..."
hashcat -a 0 -m 0 hash.txt wordlist-br/MrP4p3r
```

---

*Contributions, corrections and new Brazilian-context category suggestions are welcome via issues or pull requests.*
