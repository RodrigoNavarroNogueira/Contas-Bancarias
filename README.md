# Contas-Bancarias
Usando POO para criar contas correntes e fazer transferências

from conta import Conta
conta = Conta(123,'Rodrigo', 100, 1000)
conta.extrato
conta.deposita()
conta.saca()
conta.trasfere(valor, destino)
conta.saldo
conta.titular
conta.limite
conta.limite = novolimite
