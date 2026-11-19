# Liquid Glass Example

Exemplo de efeito de vidro líquido estilo Apple (Liquid Glass) para web.

## Uso

Abra o `index.html` no navegador ou hospede como site estático.

O efeito de glass (blur forte + highlight especular + borda iluminada) é aplicado **somente** em:
- Barras de navegação (topo e baixo)
- Botões
- Ícones

O conteúdo principal permanece limpo, sem glass.

## Técnica

- `backdrop-filter: blur(40px) saturate(180%)`
- Gradient overlay para highlight especular
- Border + inset box-shadow para profundidade e borda iluminada

Ideal para copiar a classe `.liquid-glass` em outros projetos web.

Para Expo/React Native use `expo-glass-effect` (GlassView) nos mesmos elementos.
