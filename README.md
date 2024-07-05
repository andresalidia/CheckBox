# CheckBox
#### Descrição
O projeto `CheckBoxFrame` é um exemplo simples de uma aplicação Java Swing que demonstra o uso de `JCheckBox` para alterar o estilo de uma fonte em um `JTextField`. Os checkboxes "Bold" e "Italic" permitem alternar entre estilos de fonte normal, negrito, itálico ou ambos.

#### Funcionalidades
- **JTextField**: Exibe texto com a fonte cujo estilo pode ser alterado.
- **JCheckBox "Bold"**: Ao selecionado, aplica estilo de texto em negrito.
- **JCheckBox "Italic"**: Ao selecionado, aplica estilo de texto em itálico.
- **Fonte padrão**: Inicia com uma fonte "Serif" de tamanho 14, sem negrito nem itálico.
- **Atualização dinâmica**: A fonte do `JTextField` é atualizada dinamicamente conforme os checkboxes são marcados ou desmarcados.

  
![image](https://github.com/andresalidia/CheckBox/assets/86450495/3891d21d-fca2-4cb0-b132-3dc3595a7f9a)

#### Funcionamento
Ao iniciar a aplicação, uma janela é exibida contendo o `JTextField` com texto padrão e dois checkboxes. O usuário pode marcar/desmarcar os checkboxes "Bold" e "Italic" para alterar o estilo da fonte do texto exibido no `JTextField`. A classe `CheckBoxHandler` implementa `ItemListener` para capturar os eventos de mudança de estado dos checkboxes e atualiza a fonte conforme necessário.

#### Como usar
1. Compile o código Java usando o compilador Java (`javac CheckBoxFrame.java`).
2. Execute o programa (`java CheckBoxFrame`).
3. A janela será exibida com o texto inicial e os checkboxes.
4. Marque/desmarque os checkboxes "Bold" e "Italic" para ver a mudança no estilo da fonte do texto.

![image](https://github.com/andresalidia/CheckBox/assets/86450495/14672179-13d4-4bb2-8dfc-dfb6c5c1bf83)

![image](https://github.com/andresalidia/CheckBox/assets/86450495/9586bfe6-a3dd-464a-9953-87ec753ece58)

![image](https://github.com/andresalidia/CheckBox/assets/86450495/8f47beae-a5ae-4669-838b-34e5e2e1bb88)
