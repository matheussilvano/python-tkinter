# Tkinter - Python
- Biblioteca para construção de interfaces gráficas no Python
- É uma biblioteca padrão Python, mas deve ser impotada: `import tkinter as tk`
- Criação de uma janela:
```
import tkinter as tk

root = tk.Tk()

root.geometry("800x500") # Define as proporções da janela em pixels
root.title("My fist GUI") # Define o título da janela

# Criação de um widget de texto (label)
label = tk.Label(root, text="Hello World!", font=('Arial', 18))
label.pack(padx=20, pady=20)

# Criação de uma caixa de texto para entrada do usuário (textbox)
textbox = tk.Text(root, height=3, font=('Arial', 16))
textbox.pack()

# Criação de outro tipo de caixa de entrada
myentry = tk.Entry(root)
myentry.pack(padx=10)

# Criação de botões

root.mainloop()
```
