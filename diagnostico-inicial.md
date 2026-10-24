# Diagnóstico inicial — MikroTik CHR

## Objetivo
Verificar as interfaces, os endereços IP e as rotas existentes antes de realizar alterações.

## Comandos executados
- `/interface print`
- `/ip address print`
- `/ip route print`

## Resultados

### Interfaces
ether3
ether4
lo

### Endereços IP
192.168.10.1/24 ether4

### Rotas
DAc 192.168.10.0/24 ether4

## Conclusão
O diagnóstico inicial identificou três interfaces no MikroTik CHR: `ether3`, `ether4` e `lo`.

Foi identificado o endereço IP `192.168.10.1/24` configurado na interface `ether4`, pertencente à rede `192.168.10.0/24`.

Também foi identificada uma rota diretamente conectada para essa rede, permitindo ao roteador reconhecer os dispositivos que pertencem à mesma sub-rede.

Nesta etapa, ainda é necessário verificar a função de cada interface, a configuração da rota padrão e a conectividade com outras redes.

O próximo passo será analisar os detalhes das interfaces e identificar como estão conectadas no VirtualBox antes de realizar novas configurações.
