# Como publicar o perfil no GitHub

O repositório especial **tem que se chamar exatamente** `danieldiaswolff`
(igual ao seu username). O `README.md` da branch `main` aparece no topo do perfil.

## 1. Criar o repositório no GitHub

Abra este link (já vem preenchido):

https://github.com/new?name=danieldiaswolff&description=My%20GitHub%20profile&visibility=public

- Nome: `danieldiaswolff`
- Público
- **Não** marque "Add a README" (já temos um local)

## 2. Enviar o código

```bash
cd ~/Projects/danieldiaswolff
git add .
git commit -m "Add GitHub profile README with stats and snake animation"
git push -u origin main
```

Depois do push, rode o workflow **Generate snake animation** em:
Actions → Generate snake animation → Run workflow

## 3. Completar o perfil (Settings → Profile)

Sugestão de campos:

| Campo | Valor sugerido |
|-------|----------------|
| **Name** | Daniel Dias Wolff |
| **Bio** | Full-Stack Developer \| Tech Lead \| PHP · Laravel · Node.js · React · Integrações |
| **Location** | Joinville, SC — Brasil |
| **Website** | https://www.linkedin.com/in/daniel-dias-wolff-31904819b/ |
| **Social** | LinkedIn (mesmo link) |

## 4. Fixar repositórios (Pinned)

Em https://github.com/danieldiaswolff → Customize your pins

Sugestão (enquanto os projetos de trabalho forem privados):
1. `danieldiaswolff` (este perfil)
2. `wdd131`
3. `wdd130`
4. `front-end`

Dica: adicione **description** e **topics** em cada repo público — isso muda bastante a primeira impressão.

## 5. Descrições rápidas para os repos atuais

- `wdd131` — Projetos do curso WDD 131 (web fundamentals)
- `wdd130` — Projetos do curso WDD 130 (HTML/CSS)
- `front-end` — Estudos e experimentos front-end com TypeScript
- `apiUsuariosCarros` — (já arquivado) API PHP de usuários/carros
