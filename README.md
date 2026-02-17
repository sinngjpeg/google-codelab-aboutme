# 👤 About Me – Android Codelab (Views + View Binding)

Este projeto é uma implementação do **Codelab oficial do Google – About Me**, desenvolvido com **Kotlin**, **Views tradicionais (XML)** e **View Binding**.

O objetivo do app é demonstrar conceitos básicos do desenvolvimento Android, como:

- Manipulação de Views
- Uso de View Binding
- Eventos de clique
- Atualização dinâmica da UI
- Controle do teclado (InputMethodManager)

> ❗ Este projeto **não utiliza Jetpack Compose**.

---

## 📸 Demonstração

Exemplo do app em execução:

![About Me App Screenshot](screen.png)
---

## 📱 Sobre o App

O app exibe:

- Nome do usuário
- Campo para digitar um apelido
- Botão **Done** para confirmar

### 🎯 Comportamento

1. O usuário digita um apelido
2. Ao clicar em **Done**:
   - O apelido é exibido na tela
   - O campo de texto e o botão são ocultados
   - O teclado virtual é fechado automaticamente

Esse comportamento é controlado no método:

```kotlin
private fun addNickname(view: View)
```

🧠 Conceitos Trabalhados

- ✔️ View Binding
- ✔️ Manipulação de visibilidade de Views
- ✔️ Eventos de clique (setOnClickListener)
- ✔️ Uso de InputMethodManager para esconder o teclado
- ✔️ Organização de código com apply {}

🛠 Tecnologias Utilizadas

- Kotlin
- Android SDK
- Views (XML)
- View Binding
- ConstraintLayout

### 🚀 Como Rodar o Projeto (Funciona Mesmo no Futuro)
✅ Pré-requisitos

Tenha instalado:

- Android Studio Giraffe ou superior
- SDK Android atualizado
- JDK 11+ (gerenciado automaticamente pelo Android Studio)
- Emulador Android configurado ou dispositivo físico com depuração USB

💡 O projeto utiliza Gradle Wrapper, garantindo compatibilidade mesmo com versões futuras do Android Studio.

1️⃣ Clone o repositório
````
git clone https://github.com/sinngjpeg/google-codelab-aboutme.git
cd google-codelab-aboutme
````

2️⃣ Abra no Android Studio

- Abra o Android Studio
- Clique em Open
- Selecione a pasta do projeto

3️⃣ Aguarde o Gradle Sync

O Android Studio irá automaticamente:

- Baixar dependências
- Configurar o Gradle correto
- Preparar o ambiente de build

Se aparecer algum aviso, basta aceitar as recomendações do próprio Android Studio.

4️⃣ Execute o App

- Escolha um emulador ou dispositivo físico
- Clique em Run ▶
- Ou use o atalho Shift + F10

O app será instalado e iniciado automaticamente.

### 📂 Estrutura do Projeto
````
.
├── app/
│   ├── src/main/java/com/sinngjpeg/aboutme/
│   │   ├── MainActivity.kt
│   │   └── MyName.kt
│   ├── src/main/res/
│   │   ├── layout/
│   │   ├── values/
│   │   └── drawable/
│   └── build.gradle
├── gradle/
├── build.gradle
├── settings.gradle
└── README.md
````

### 📚 Recursos Oficiais

- [Android Developers](https://developer.android.com)
- [View Binding](https://developer.android.com/topic/libraries/view-binding)
- [Codelabs Android](https://developer.android.com/codelabs)
