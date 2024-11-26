# DER-Mecanica-Power
DER de um exercício sobre Ordens de Serviço de uma Oficina Mecânica

**Relacionamentos:**

* Um cliente pode ter vários veículos.
* Cada veículo pode gerar várias ordens de serviço.
* Uma ordem de serviço pode ter vários serviços e incluir várias peças.
* Uma equipe é composta por vários mecânicos e é responsável pela execução de uma OS.


**Modelo Conceitual**

A representação conceitual do sistema pode ser expressa da seguinte forma:

* Cliente (1:N) Veículo
* Veículo (1:N) Ordem de Serviço
* Ordem de Serviço (1:N) Serviço
* Ordem de Serviço (1:N) Peça
* Equipe (1:N) Ordem de Serviço
* Equipe (N:M) Mecânico
