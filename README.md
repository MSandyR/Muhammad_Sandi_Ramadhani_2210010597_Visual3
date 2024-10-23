import PySimpleGUI as sg
 sg.theme("DarkGreen4")
 sg.theme_text_color("#FFFF00")
 window = sg.Window(title="Profile",
        layout=[[sg.Text("SELAMAT DATANG DI KELAS",
                font=("Arial",25,"italic","bold","underline"))],
            [sg.Text("NPM   : 2210010587 ")],
            [sg.Text("Nama  : Muhammad Sandi Ramadhani ")],
            [sg.Text("Kelas : 5A Non Reg Banjarmasin ")]
            ],
        size=(510,200),
        font=("Times", 18))
 window()
 window.close()

 
