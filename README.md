# Layouts
Cada tipo de Layout

O FrameLayout é o tipo de layout mais simples no Android. Ele funciona como uma pilha, colocando os elementos um sobre o outro. É útil quando você precisa mostrar apenas um item ou sobrepor componentes, como colocar um texto em cima de uma imagem de fundo ou exibir um vídeo em tela cheia. Um exemplo comum é a tela de splash ou um player de vídeo.

Já o LinearLayout organiza os elementos em linha, podendo ser na vertical ou na horizontal. Ele é indicado para quando você precisa de uma estrutura simples, em que os elementos aparecem em sequência, um abaixo do outro ou lado a lado. É muito usado em formulários, listas pequenas de botões ou configurações rápidas, já que deixa tudo alinhado de forma ordenada.

O RelativeLayout traz mais flexibilidade, permitindo que os elementos sejam posicionados em relação ao pai ou entre si. Por exemplo, você pode colocar um botão à direita de um texto ou uma imagem centralizada na tela. Esse tipo de layout é bastante útil em telas como a de login, onde os componentes precisam de um posicionamento mais específico e organizado sem depender apenas de linhas.

O ConstraintLayout, por sua vez, é o mais moderno e poderoso. Ele funciona por meio de restrições (constraints), que definem como cada elemento deve se relacionar com outros componentes ou com o contêiner. É o layout mais indicado para criar telas complexas e responsivas, já que permite adaptar melhor a interface a diferentes tamanhos de tela. Atualmente, ele substitui o uso do RelativeLayout e do LinearLayout em muitos casos, sendo muito usado em telas principais de aplicativos modernos.

Por fim, o RecyclerView não é exatamente um layout, mas um componente pensado para listas dinâmicas e longas. Ele é muito mais performático que o antigo ListView, já que reaproveita os elementos que saem da tela em vez de recriá-los o tempo todo. É a escolha ideal para quando você precisa exibir listas grandes ou infinitas, como um feed de redes sociais, uma lista de contatos ou um catálogo de produtos em um aplicativo de compras.
