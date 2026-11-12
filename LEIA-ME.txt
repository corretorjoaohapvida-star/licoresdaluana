# Licores da Luana

Landing page estática da Chef Luana Araújo. Arquivos prontos na raiz: HTML, JavaScript, CSS, fontes e imagens locais. Sem etapa de build no servidor.

## Publicação na Vercel

Importar este repositório, selecionar framework `Other`, diretório raiz `./`, sem comando de build e sem diretório de saída personalizado. O `index.html` da raiz é a entrada. Nenhuma variável de ambiente é necessária.

## Checkouts

Os links em `config.js` foram fornecidos pelo proprietário: Básico R$ 10 (50 receitas), Completo R$ 29,90 (150 receitas e seis bônus) e upgrade R$ 19,90. Os parâmetros UTM, fbclid, src e sck recebidos são preservados nos links de pagamento quando configurados.

Os links fornecidos substituem os checkouts anteriores. A entrega e o recebimento de pagamentos nesses novos checkouts não foram validados por compra de teste. Subir o código não altera a configuração dos produtos na Cakto.

## Pixel

Meta Pixel `30229346923321953`, evento `PageView`, inicializado uma vez. Não há evento Purchase na landing. O recebimento deve ser conferido no Gerenciador de Eventos após publicação em HTTPS; não foi validado por este upload.

## Verificação

Interações, arquivos locais, links e bootstrap do pixel verificados em JSDOM. Chrome foi bloqueado pelo ambiente (`spawn EPERM`), impedindo medição real de layout mobile, LCP e rede. Sem compra de teste. Não confundir aprovação dos testes locais com validação da entrega ou do pagamento.
