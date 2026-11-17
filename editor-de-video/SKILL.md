---
name: editor-de-video
description: Configura um editor de vídeo para a marca do usuário, analisa referências com /watch e edita vídeos a partir de uma narração ou gravação. Use para criar um estilo de edição ou produzir Reels, Shorts e outros vídeos seguindo uma identidade visual.
---

# Editor de Vídeo

Use o fluxo do Cleiton com a identidade do usuário atual. Aproveite o que ele já enviou e peça só o que falta. Guarde o nome, a identidade visual e as preferências confirmadas em `PERFIL-DO-EDITOR.md` no projeto. Reaproveite esse perfil entre vídeos da mesma marca.

## 1. Conheça a marca

Na primeira edição, peça o nome que a pessoa quer dar ao editor e o nome da pessoa ou marca que deve aparecer no vídeo. Peça a paleta de cores (HEX, print ou manual), fontes e logo ou assinatura se houver. Um manual ou perfil visual já fornecido pode responder a essas perguntas. Confirme plataforma e formato quando não estiverem claros. Pergunte sobre público, objetivo ou restrições apenas quando mudarem a montagem.

Peça também de 1 a 3 referências de vídeo, como links ou arquivos, e pergunte o que a pessoa quer aproveitar de cada uma, se souber. Use quantas ela enviar. Se faltar uma informação de marca que altere o resultado, solicite o elemento específico ou ofereça uma proposta para ela escolher.

## 2. Analise as referências com /watch

Localize a skill `watch`, leia seu `SKILL.md` e use o fluxo documentado para analisar cada referência relevante. `/watch` é a forma de acionar essa análise. Se o ambiente expõe a skill como `$watch`, use essa forma ou o script da própria skill. Para arquivos locais e mídia privada, use o modo local. Use transcrição local quando disponível e complemente frames com trechos que ajudem a entender ritmo, transição e timing. Quando necessário, peça os arquivos ou trechos acessíveis de links que falharem. Se `watch` estiver indisponível, explique a dependência e aproveite o material que puder examinar localmente. Identifique quais observações a análise parcial sustenta.

Crie ou atualize um `GUIA-DE-EDICAO.md` no projeto. Anote tempos relevantes e converta as observações em regras que possam ser usadas em novos vídeos. Cubra abertura, ordem das cenas, ritmo dos cortes, enquadramento, legendas, tipografia, uso da paleta, motion, transições, trilha e efeitos sonoros. Para cada escolha importante, indique como adaptá-la à identidade da pessoa. Apresente a direção em poucas linhas. Quando já existir um guia da mesma marca, reaproveite-o e analise as referências novas que a pessoa enviar.

## 3. Peça os arquivos do vídeo

Apresente a direção e peça a narração pronta ou a gravação original, junto com a trilha desejada. A pessoa pode mandar o arquivo, indicar gênero e energia para você escolher, ou optar por um vídeo sem música. Peça roteiro, clipes, telas e imagens só quando forem necessários para a montagem. Se a fala mandar comentar uma palavra ou código, confirme o termo quando ele não estiver claro.

Com o material já disponível, avance direto para a montagem. Se faltar a trilha, avance com cortes e cenas enquanto a pessoa decide.

## 4. Edite, confira e entregue

Leia [Montagem e entrega](references/montagem-e-entrega.md) ao iniciar a montagem. Use Remotion por padrão para compor e renderizar, com FFmpeg para áudio, recortes e conferência. Se a pessoa já trabalha com outro editor e o pedir, use o fluxo dessa ferramenta.

Entregue o MP4 no destino combinado, com link para abrir, e cite decisões que a pessoa precisa conferir. Entregue créditos quando aplicável e o projeto editável quando solicitado. Se a pessoa pedir para limpar os intermediários ou tiver combinado a limpeza na aprovação, valide a entrega no destino e preserve os originais e arquivos compartilhados durante a limpeza.
