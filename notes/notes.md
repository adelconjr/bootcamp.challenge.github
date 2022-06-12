# **Gerar par de chaves SSH para usar no GitHub**

>`ssh-keygen -t ed25519 -C <email>`

1. Escolha o local onde salvar as chaves (deixar padrão se não souber)

2. Colocar senha

3. Chaves geradas no local escolhido :chart:

**Para ver as chaves criadas, navegue até a pasta escolhida anteriormente para salvar as chaves, e digite:**

>`cat <chave_publica.pub>`

Copie e cole a  chave publica no github :tada:

___

## Comando para usar a chave privada no pc (ssh agent)

1. Execute o ssh agent
>`eval $(ssh-agent -s)`
2. Adicione a chave privada ao ssh agent
>`ssh-add <nome_da_chave_privada>`
3. Digite a senha
4. Chaves configuradas! :tada:


