# JDBCTransacoes

API
* setAutoCommit(true) confirma cada operação declarada se estiver valendo verdadeiro
* commit() confirmar a operação
* rollback() desfazer o que foi feito até o momento

ATOMICA -> ou acontece tudo ou não acontece nada
CONSISTENTE -> os dados estão em um estdado consistente quando uma trasação começa e quando termina.
ISOLAMENTO -> o estado intermediario de uma transação é invisivel para outras. Como resultado, as transações executadas simutaneamente parecem se serializadas.
DURABILIDADE -> após a conclusão bem sucedida de uma transação, as alterações nos dados persistem e não são desfeitas, mesmo no caso de falha do sistema.
