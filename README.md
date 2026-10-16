# TekPrint

Imprima recibos e documentos do POS TekSoft nas impressoras do seu computador.

**Requisitos:** Windows de 64 bits, impressora instalada e ligada, e acesso ao POS.

Actualmente, a integração utiliza navegadores baseados em **Chromium**: **Google Chrome, Microsoft Edge e Brave**. Mantenha o navegador actualizado.

## 1. Instalar

1. Em **Releases**, escolha a versão do **TekPrint** indicada para instalação.
2. Descarregue o instalador **TekPrint-Setup-[versão].exe**.
3. Execute o instalador e abra o **TekPrint**.

## 2. Configurar o POS

1. Em **POS**, introduza o endereço completo do POS, começando por `https://`.
2. Clique em **Adicionar endereço** e confirme a **Página inicial do POS**.
3. Clique em **Guardar endereços** e depois em **Continuar: gerar extensão**.

## 3. Instalar a extensão

1. Em **Extensão**, seleccione o navegador utilizado no POS.
2. Clique em **Escolher pasta e gerar extensão** e seleccione uma pasta permanente.
3. Clique em **Abrir extensões no navegador**.
4. Active o **Modo de programador** e escolha **Carregar sem compactação**, ou a opção equivalente.
5. Seleccione a pasta criada pelo TekPrint, confirme que a extensão está activa e actualize o POS.

**Não mova nem elimine a pasta da extensão após a instalação.**

## 4. Configurar as impressoras

Em **Impressoras**, associe cada formato à impressora correspondente:

| Formato | Método |
|---|---|
| Recibo de 80 mm | **ESC/POS**, numa impressora compatível com impressão gráfica |
| Documento A4 | **Driver do Windows** |

Para 80 mm, comece com **576 pontos**. Ajuste apenas se a impressora exigir outra largura.

Clique em **Guardar impressora** e em **Imprimir teste**. Confirme o resultado antes de imprimir vendas.

## Utilização diária

- Mantenha o TekPrint aberto. Pode minimizá-lo enquanto trabalha.
- No POS, finalize a venda e escolha **Térmico** ou **A4**.
- Aguarde a mensagem de estado. Se o resultado for incerto, verifique a impressora antes de pedir outra cópia.
- Para iniciar o agente com o computador, active **Iniciar automaticamente ao entrar no Windows**, em **Preferências**.

## Actualizar

Feche o navegador e o TekPrint. Instale a nova versão disponível em **Releases** e reabra a aplicação. As configurações e o histórico são preservados.

Se a actualização indicar alterações à extensão, gere-a novamente e recarregue-a no navegador.

## Se não conseguir imprimir

Confirme que o TekPrint está aberto, a extensão está activa e a impressora tem papel e está ligada. Se necessário, utilize **Reparar integração local**, no separador **Extensão**.

Se persistir, contacte o suporte e indique a mensagem de erro e o modelo da impressora.
