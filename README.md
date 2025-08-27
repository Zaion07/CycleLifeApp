# 📱 CycleLifeApp

Um aplicativo Android simples desenvolvido em **Kotlin** com **XML layouts**, criado como atividade prática para demonstrar:

- **Navegação entre duas telas (Activities)**  
- **Uso dos métodos do ciclo de vida das Activities**  
- **Registro de logs no Logcat**  

---

## 🚀 Funcionalidades

- Tela inicial com texto e botão **"Verificar"**.  
- Ao clicar em **"Verificar"**, o app abre a segunda tela.  
- A segunda tela mostra um texto fixo **"Ciência da Computação"** e um botão **"Voltar"**.  
- O botão **"Voltar"** retorna para a primeira tela.  
- Cada Activity implementa todos os métodos do ciclo de vida:  
  - `onCreate()`  
  - `onStart()`  
  - `onResume()`  
  - `onPause()`  
  - `onStop()`  
  - `onRestart()`  
  - `onDestroy()`  
- Cada método exibe mensagens no **Logcat** usando `Log.i`, para acompanhar a ordem de execução.

---

## 🛠️ Tecnologias Utilizadas

- **Kotlin** (linguagem principal)  
- **Android SDK**  
- **AppCompatActivity** (para compatibilidade com temas e recursos modernos)  
- **Layouts XML**  


## 📂 Estrutura do Projeto

