# LifeOS — pacote PWA

Arquivos (todos na mesma pasta, sem subpastas — assim dá para enviar pelo celular):
index.html · manifest.json · service-worker.js · icon-192.png · icon-512.png · icon-maskable-512.png · apple-touch-icon.png · favicon-32.png

## Publicar de graça no GitHub Pages (pelo navegador do celular)
1. No Chrome do celular, abra github.com e crie uma conta gratuita.
2. Menu ⋮ do Chrome → marque "Site para computador" (facilita os botões abaixo).
3. Toque em "+" → "New repository". Nome: lifeos. Marque "Public". Toque em "Create repository".
4. Na página do repositório: "Add file" → "Upload files". Toque na área de upload e selecione os 8 arquivos (a seleção múltipla do Android permite escolher todos de uma vez; subpastas não são necessárias). Toque em "Commit changes".
5. Aba "Settings" → "Pages" → em "Branch" escolha "main" e "/ (root)" → "Save".
6. Aguarde 1–3 minutos. O endereço será: https://SEU-USUARIO.github.io/lifeos/ (aparece no topo da página Pages).

## Instalar no Samsung Galaxy A16
1. Abra o endereço HTTPS acima no Google Chrome.
2. Menu ⋮ → "Instalar app" (ou "Adicionar à tela inicial" → "Instalar"). Também pode aparecer o cartão "Instalar app" no painel inicial.
3. Abra o LifeOS pelo ícone na tela inicial.

## Proteger seus dados
- Os dados ficam só neste aparelho, no armazenamento do navegador (localStorage). Não há sincronização.
- Limpar os dados do Chrome/do site, ou desinstalar, pode apagar tudo.
- Faça backup: Início → "Exportar" → "Copiar" e cole em Notas, e-mail ou mensagem para você mesmo. Faça isso toda semana e antes de qualquer limpeza do celular.
- Restaurar: Início → "Importar" → cole o texto (ou escolha o arquivo) → confirme.
- Importante: mantenha sempre o MESMO endereço. Outro endereço (ou domínio) é outro armazenamento, sem seus dados — use Importar para levá-los.

## Publicar uma atualização
Envie o novo index.html ao repositório (Add file → Upload files, mesmo nome, substitui). Para forçar a renovação do cache offline, mude CACHE='lifeos-v1' para v2 em service-worker.js. Seus dados não são afetados.
