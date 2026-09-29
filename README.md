# Vibe Hack Black

Landing page em português para uma proposta de edição em homenagem à Consciência Negra. HTML, CSS e JavaScript, sem dependências de instalação ou build.

## Executar

```sh
npm run dev
```

Abra http://localhost:3000. Use `PORT=8080 npm run dev` para outra porta. Requer Node.js 18 ou superior. Para hospedar estaticamente, publique `index.html`, `style.css`, `script.js` e `assets/`.

## Conteúdo e publicação

Data, local, formato, elegibilidade, equipes, programação e inscrições da edição Black não foram informados. A página sinaliza essas informações como pendentes e não coleta dados nem simula inscrições. Antes da publicação oficial, valide o texto com a organização, atualize as respostas em `#duvidas` e substitua o status em `#participe` pelo link oficial de inscrição.

O e-mail de contato `vibehack@cin.ufpe.br` é o divulgado nas notícias do evento. A identidade acompanha as referências: hero centralizado, fundo preto com grade, código flutuante, tipografia monoespaçada, brilho nos títulos e botões de alto contraste. Laranja é a cor principal da edição Black, com detalhes secundários em verde e vermelho. As fontes Inter e Space Mono são carregadas do Google Fonts, com fallback local. Nenhuma imagem externa é necessária. Os SVGs originais em `assets/` trazem uma faixa geométrica decorativa e um retrato afrofuturista. A página incorpora esses grafismos diretamente no HTML para que apareçam sem requisições extras ou carregamento tardio. Os grafismos não são apresentados como símbolos tradicionais de uma cultura específica.

## Referências

- [Vibe Hack](https://vibehack.cin.ufpe.br/) e [anúncio da primeira edição](https://portal.cin.ufpe.br/2025/06/05/cin-ufpe-anuncia-o-vibe-hack-novo-hackathon-com-vibe-coding/)
- [Vibe Hack GRRRL](https://vibehack.cin.ufpe.br/hackgrrrl/), [CIn-UFPE](https://portal.cin.ufpe.br/2026/03/26/nova-edicao-do-vibe-hack-abre-inscricoes-com-edicao-especial-voltada-a-mulheres-e-iniciantes-em-tecnologia/) e [Jornal Digital](https://jornaldigital.recife.br/2026/03/31/hackathon-do-cin-ufpe-abre-inscricoes-para-edicao-com-foco-em-mulheres-e-iniciantes/)
- [Vibe Hack Queer](https://vibehack.cin.ufpe.br/queer/) e [relato do CIn-UFPE](https://portal.cin.ufpe.br/2026/07/03/vibe-hack-queer-do-cin-ufpe-reune-estudantes-em-competicao-voltada-a-diversidade/)
- [Vibe Hack Bari](https://vibehack.cin.ufpe.br/bari/) e [publicação do SERLAB](https://www.linkedin.com/posts/serlablaboratory_vibehack-hackathon-techforgood-activity-7416857984217206784-aqMt)

O Instagram fornecido não ficou acessível durante a pesquisa. O conteúdo foi fundamentado nas notícias e publicações acessíveis; não foram reutilizados regulamentos ou promessas das outras edições.

## Verificação

`npm run check` verifica a sintaxe JavaScript. A página inclui navegação móvel, FAQ nativo, foco visível, link de pular conteúdo e respeito à preferência por movimento reduzido.
