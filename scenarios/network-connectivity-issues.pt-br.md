# Falhas de conectividade de rede 🛜

## Descrição
O usuário relata que não consegue acessar a internet ou serviços internos. Isso pode acontecer no Wi-Fi ou na rede cabeada, podendo ser algo temporário ou persistente.

## Possíveis causas 🛠️
- Wi-Fi desconectado ou conectado na rede errada
- Cabo de rede solto ou danificado
- IP não atribuído corretamente (problema de DHCP (significado nas observações))
- Falha de DNS (alguns sites/sistemas não abrem)
- Instabilidade temporária ou manutenção na rede

## Verificações iniciais 🔎
1. Perguntar se outras pessoas/dispositivos estão com o mesmo problema (mesmo local/rede)
2. Confirmar se é Wi-Fi ou cabo e em qual rede o usuário está conectado
3. Checar o status da conexão no sistema (ícone de rede e detalhes básicos)
4. Pedir para reconectar o Wi-Fi ou retirar/colocar o cabo novamente
5. Se permitido, fazer um teste simples (ex.: ping no gateway / abrir um sistema interno conhecido)

## Ações recomendadas ✅
- Conectar na rede correta e testar novamente
- Reiniciar o equipamento se o problema continuar e não houver indisponibilidade geral
- Renovar o IP se o equipamento não estiver recebendo endereço
- Encaminhar para infraestrutura/redes se houver impacto em vários usuários

## Observações 📝
Registrar o que foi testado e os resultados (o que funcionou e o que não funcionou). Isso ajuda muito ao escalar.

O DHCP é o "garçom" da rede: assim que um dispositivo se conecta (Wi-Fi ou cabo), o DHCP entrega automaticamente o "crachá" (endereço IP) e as instruções necessárias para ele conseguir navegar na internet.
