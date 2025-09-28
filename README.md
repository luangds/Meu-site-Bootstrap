# Meu-site-Bootstrap
Um template do Bootstrap modificado.

�
� Álbum Bootstrap - Customizado
 Este projeto é baseado no template Album example do 
Bootstrap. Foram realizadas diversas
 alterações e melhorias para torná-lo mais interativo e personalizável.
 🚀 Alterações implementadas
 1. Estrutura do projeto
 • 
• 
Separação do arquivo de estilos em 
styles.css para melhor organização do código.
 Inclusão de um arquivo 
favicon.png (exemplo fornecido).
 2. Estilização
 • 
• 
Ajustes no CSS para garantir que as imagens tenham proporção adequada (
 cover ).
 Seção do álbum com espaçamento e cor de fundo (
 3. Funcionalidades novas
 🔍 Modal de visualização ampliada
 • 
• 
.album ).
 object-fit: 
Ao clicar em "Ver", a imagem abre em destaque dentro de um modal Bootstrap.
 O modal exibe:
 • 
• 
• 
• 
• 
• 
• 
• 
Imagem em tamanho maior
 Título
 Descrição
 Navegação entre imagens com botões Anterior e Próxima.
 Suporte opcional para atalhos de teclado:
 ← (esquerda): imagem anterior
 → (direita): próxima imagem
 Esc : fecha o modal
 4. Correções
 • 
O modal agora lê os dados diretamente do DOM (através de atributos 
data-* ou do conteúdo
 do card), evitando inconsistência entre a miniatura e a versão ampliada.
 📂 Estrutura de arquivos
 / (raiz do projeto)
 ├── index.html        # Página principal com o álbum
 ├── styles.css        # Estilos personalizados
 ├── favicon.png       # Ícone do site
 └── /img              # Pasta sugerida para imagens do álbum
 1
�
� Como usar
 1. 
2. 
Substitua as imagens de exemplo (
 <img src="..."> ) pelas suas próprias.
 Ajuste os botões Ver adicionando 
data-src , 
data-title e 
o conteúdo exibido no modal. 
data-desc se quiser controlar
 <button type="button" class="btn btn-sm btn-outline-secondary view-btn"
 data-src="img/foto-grande.jpg"
 data-title="Título da Foto"
 data-desc="Descrição detalhada da foto">
  Ver
 </button>
 3. 
Abra 
index.html no navegador.
 ✨ Próximos passos (ideias de evolução)
 • 
• 
• 
• 
• 
Filtros por categoria (ex.: Natureza, Retratos, Cidade).
 Busca por texto nas descrições.
 Layout estilo Masonry (tipo Pinterest).
 Integração com APIs de imagens (Unsplash, Pexels).
 Upload de imagens pelo usuário.
 📌 Desenvolvido a partir do template oficial do Bootstrap com melhorias para aprendizado e prática
