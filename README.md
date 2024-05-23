# Loja de Cogumelos em Java

CRUD's (Cadastro, Alteração, Deleção e Listagem):

Para cada entidade do sistema (como Produto, Cliente, Pedido, etc.), implemente métodos para:
Cadastrar um novo item. Alterar informações de um item existente. Deletar um item. 
Listar todos os itens ou buscar por critérios específicos.
Relação entre CRUD's:

Identifique as relações entre as entidades do sistema e estabeleça as associações apropriadas. Por exemplo:
Um Pedido pode conter vários Produtos. Um Cliente pode fazer vários Pedidos.
Implemente essas relações através de atributos nas classes ou usando tabelas intermediárias, dependendo do seu modelo de dados.
Super Classe:

Crie uma classe abstrata.
Adicione atributos comuns a todas as entidades do sistema, como id, nome, descricao, etc.
Implemente métodos getter e setter para esses atributos.
Classe Abstrata:

Identifique comportamentos comuns entre diferentes tipos de objetos do seu 
sistema (por exemplo, diferentes tipos de cogumelos) e crie uma classe abstrata para representá-los.
Defina métodos abstratos que devem ser implementados pelas subclasses.

Polimorfismo de Sobrescrita:

Sobrescreva métodos da classe pai nas subclasses para adaptá-los às suas necessidades específicas.
Por exemplo, você pode sobrescrever o método calcularPreco() na classe abstrata Produto e implementá-lo de forma diferente em cada tipo de cogumelo.
Polimorfismo de Sobrecarga:

Sobrecarregue métodos com o mesmo nome, mas com assinaturas diferentes, para lidar com diferentes situações.
Por exemplo, você pode ter vários métodos adicionarProduto() na classe Carrinho, cada um aceitando diferentes tipos de parâmetros ou realizando diferentes operações.

Interface:

Identifique comportamentos comuns que devem ser implementados por diferentes classes e defina uma interface que represente esses comportamentos.
Por exemplo, você pode ter uma interface Vendavel com métodos como calcularPreco() e getNome() que todas as classes de produto devem implementar.
Encapsulamento:

Defina os atributos das suas classes como privados para garantir o encapsulamento.
Forneça métodos getter e setter públicos para acessar e modificar os atributos, quando necessário.
MVC (Model, View e Controller):


Organize o projeto em três camadas distintas:
Model: Contém a lógica de negócio, como classes de entidades e operações CRUD.
View: Responsável pela interface com o usuário, como telas de cadastro, listagem e carrinho de compras.
Controller: Coordena as interações entre o Model e a View, recebendo solicitações do usuário, chamando os métodos apropriados no Model e atualizando a View conforme necessário.
Utilizar estruturas de laço e controle:

Utilize estruturas de laço (for, foreach, while ou do while) e estruturas de controle (if, else if, else ou switch) 
conforme necessário para controlar o fluxo do programa e iterar sobre listas de itens.
Log:

Crie uma classe de log que seja responsável por escrever informações relevantes em um arquivo de texto.
Implemente métodos para registrar eventos específicos, como erros ou atividades do sistema.
Utilize a classe FileWriter para escrever no arquivo de log.
Serialização:

Implemente métodos de serialização e desserialização nas classes que precisam ser salvadas e recuperadas.
Utilize as classes ObjectOutputStream e ObjectInputStream para salvar e carregar objetos em arquivos.
