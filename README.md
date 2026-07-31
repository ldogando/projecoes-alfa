# Projeções de Alfabetização — Curvas de Alfa

**Explorador interativo** das curvas de alfabetização por UF (2023–2031), a partir do Indicador Criança Alfabetizada (ICA/AEEB, INEP). Permite escolher o cenário de projeção e a UF em destaque para comparar trajetórias. 

🔗 **Página publicada:** `https://<seu-usuario>.github.io/projecoes-alfa/`

## Acesso

O conteúdo é **protegido por senha**. Ao abrir a página, é preciso informar a senha de acesso para visualizar o material.

A senha é compartilhada **separadamente** e não fica registrada neste repositório. O arquivo publicado guarda o conteúdo **criptografado** (AES-GCM, chave derivada da senha via PBKDF2), então quem não tem a senha não consegue ler os dados — nem pelo código-fonte da página.

## O que tem aqui

| Arquivo | Descrição |
| :---- | :---- |
| `index.html` | A página protegida. Contém o explorador interativo criptografado \+ a tela de acesso. É o único arquivo necessário para o site funcionar. |
| `README.md` | Este arquivo. |
| `INSTRUCOES-PUBLICACAO.md` | Passo a passo para publicar e atualizar a página. |

## Conteúdo do painel

Explorador com dois controles: **Base** (o cenário de projeção — tendência, tendência PARC/\~PARC, ritmos de referência como Ceará e Top3, meta oficial etc.) e **UF em destaque**. A partir da seleção, o gráfico mostra a série histórica e a projeção da UF em relação às demais e à Meta Aliança de 95%.
