# laboratorio-mikrotik-virtualbox
Laboratório prático de configuração de redes com MikroTik CHR no VirtualBox.
# Laboratório MikroTik CHR no VirtualBox

## 1. Objetivo

Este projeto tem como objetivo praticar configurações de redes utilizando o MikroTik CHR em um ambiente virtualizado.

## 2. Ferramentas utilizadas

- Oracle VirtualBox
- MikroTik CHR (Cloud Hosted Router)
- MikroTik RouterOS
- Terminal de comandos

## 3. Topologia da rede

O laboratório será desenvolvido utilizando um roteador MikroTik virtual e adaptadores de rede configurados no VirtualBox.

**Componentes:**
- MikroTik CHR: roteador virtual.
- ether1: interface de rede a ser identificada e configurada.
- ether2: interface de rede a ser identificada e configurada.
- Máquina cliente: será utilizada nos testes, quando configurada.

## 4. Atividades práticas

- [ ] Identificar as interfaces de rede.
- [ ] Consultar os endereços IP existentes.
- [ ] Configurar IP e máscara de rede.
- [ ] Configurar DHCP.
- [ ] Configurar rotas.
- [ ] Configurar NAT.
- [ ] Testar a conectividade.
- [ ] Registrar os resultados dos testes.

## 5. Comandos de diagnóstico

Consultar as interfaces:

```routeros
/interface print
```

Consultar os endereços IP:

```routeros
/ip address print
```

Consultar as rotas:

```routeros
/ip route print
```

## 6. Evidências

As capturas de tela e os resultados dos testes serão adicionados conforme as atividades forem concluídas.

## 7. Aprendizados

Este projeto será atualizado com os comandos executados, a explicação de cada configuração e os problemas identificados e resolvidos durante a prática.

## 8. Status

Em desenvolvimento.
