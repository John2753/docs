---
title: Managing categories for discussions
intro: 'You can categorize discussions to organize conversations for your community members, and you can choose a format for each category.'
permissions: Repository administrators and people with write or greater access to a repository can manage categories for discussions in the repository. Repository administrators and people with write or greater access to the source repository for organization discussions can manage categories for discussions in the organization.
versions:
  fpt: '*'
  ghec: '*'
shortTitle: Gerenciar categorias
redirect_from:
  - /discussions/managing-discussions-for-your-community/managing-categories-for-discussions-in-your-repository
---


## Sobre categorias para discussões

{% data reusables.discussions.about-discussions %} {% data reusables.discussions.about-categories-and-formats %}

{% data reusables.discussions.about-announcement-format %}

Cada categoria deve ter um nome e um pareamento de emojis únicos e pode ser acompanhada de uma descrição detalhada que informa o seu propósito. As categorias ajudam os mantenedores a organizar como as conversas são arquivadas e são personalizáveis para ajudar a distinguir categorias que são Q&A (perguntas e respostas) ou conversas mais abertas. {% data reusables.discussions.repository-category-limit %} Para obter mais informações, consulte "[Sobre discussões](/discussions/collaborating-with-your-community-using-discussions/about-discussions#about-categories-and-formats-for-discussions)".

## Categorias-padrão

| Categoria          | Finalidade                                                                 | Formato             |
|:------------------ |:-------------------------------------------------------------------------- |:------------------- |
| 📣 Anúncios         | Atualizações e notícias de mantenedores do projeto                         | Anúncio             |
| #️⃣ Geral          | Tudo que for relevante para o projeto                                      | Discussão aberta    |
| 💡 Ideias           | Ideias para alterar ou melhorar o projeto                                  | Discussão aberta    |
| 🗳 Polls            | Polls with multiple options for the community to vote for and discuss      | Polls               |
| 🙏 Q&A              | Perguntas para a comunidade responder, com um formato de pergunta/resposta | Pergunta e resposta |
| 🙌 Mostrar e contar | Criações, experimentos ou testes relevantes para o projeto                 | Discussão aberta    |

## Criar categoria

1. On {% data variables.product.product_location %}, navigate to the main page of the repository or organization where you want to create a category.
{% data reusables.discussions.discussions-tab %}
{% data reusables.discussions.edit-categories %}
1. Clique em **Nova Categoria**. ![Botão "Nova categoria" acima da lista de categorias de discussão para um repositório](/assets/images/help/discussions/click-new-category-button.png)
1. Edite o emoji, título, descrição e formato de discussão para a categoria. Para obter mais informações sobre formatos de discussão, consulte "[Sobre discussões](/discussions/collaborating-with-your-community-using-discussions/about-discussions#about-categories-and-formats-for-discussions)". ![Emoji, título, descrição e formato de discussão para a nova categoria](/assets/images/help/discussions/edit-category-details.png)
1. Clique em **Criar**. ![Botão "Criar" para uma nova categoria](/assets/images/help/discussions/new-category-click-create-button.png)

## Editar uma categoria

Você pode editar uma categoria para alterar o emoji, título, descrição e formato da discussão.

1. On {% data variables.product.product_location %}, navigate to the main page of the repository or organization where you want to create a category.
{% data reusables.discussions.discussions-tab %}
1. À direita de uma categoria na lista, clique em {% octicon "pencil" aria-label="The pencil icon" %}. ![Botão de editar à direita da categoria na lista de categorias para um repositório](/assets/images/help/discussions/click-edit-for-category.png)
1. {% data reusables.discussions.edit-category-details %}![Editar emoji, título, descrição e formato de discussão para uma categoria existente](/assets/images/help/discussions/edit-existing-category-details.png)
1. Clique em **Save changes** (Salvar alterações). ![Botão "Salvar as alterações" para a categoria existente](/assets/images/help/discussions/existing-category-click-save-changes-button.png)

## Excluir uma categoria

Ao você excluir uma categoria, {% data variables.product.product_name %} moverá todas as discussões da categoria excluída para uma categoria existente que você escolher.

1. On {% data variables.product.product_location %}, navigate to the main page of the repository or organization where you want to create a category.
{% data reusables.discussions.discussions-tab %}
1. À direita de uma categoria na lista, clique em {% octicon "trash" aria-label="The trash icon" %}. ![Botão de lixeira à direita da categoria na lista de categorias para um repositório](/assets/images/help/discussions/click-delete-for-category.png)
1. Use o menu suspenso e escolha uma nova categoria para qualquer discussão na categoria que você está excluindo. ![Menu suspenso para escolher nova categoria ao excluir uma categoria existente](/assets/images/help/discussions/choose-new-category.png)
1. Clique em **Excluir & Mover**. ![Menu suspenso para escolher nova categoria ao excluir uma categoria existente](/assets/images/help/discussions/click-delete-and-move-button.png)
