Trabalho Prático 2
O objetivo deste trabalho é aplicar os algoritmos distribuídos.

Descrição do Problema.

Neste trabalho prático, você deve implementar o algoritmo de Exclusão Mútua Centralizado e o algoritmo de eleição do Anel, para definir o Coordenador.

O sistema distribuído sempre deve ter um líder, caso um computador desconecte/falhe, outro líder deve ser escolhido.
O recurso acessado deve ser um arquivo, este arquivo deve ficar centralizada em dispositivo da rede, enquanto que o dispositivo que realizar o acesso deve colocar seu hostname e o timestamp no arquivo.
As solicitações de acesso ao recurso devem ser geradas de forma aleatória.
Cada dispositivo deve ter seu próprio ID distinto.
A rede deve possuir no mínimo 4 dispositivos distintos.