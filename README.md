# Gerenciamento de Memória em Rust 💻

Este projeto contém uma coleção de exemplos de código em Rust que demonstram conceitos essenciais de gerenciamento de memória. Através de exemplos práticos, você aprenderá como o Rust lida com memória de maneira segura e eficiente, sem a necessidade de um coletor de lixo.

## Conceitos Abordados 📚

- **Ownership e Borrowing**: Compreenda como o Rust gerencia a propriedade de variáveis e permite que você empreste dados de forma segura.
- **Lifetimes**: Explore como o Rust garante que referências vivam por tempo suficiente para evitar o uso de memória inválida.
- **Smart Pointers**: Aprenda sobre ponteiros inteligentes, como `Box`, `Rc` e `Arc`, e como eles ajudam a gerenciar memória de maneira eficiente.
- **Borrow Checker**: Entenda como o compilador do Rust valida as regras de empréstimo de dados para garantir a segurança da memória.
- **Zero-Cost Abstractions**: Veja como Rust oferece abstrações poderosas que não adicionam sobrecarga em tempo de execução, ou seja, sem custo adicional de performance.

## Como Abrir a Documentação 📖

Para compilar e visualizar a documentação localmente, use o seguinte comando no terminal:

```bash
cargo doc --open
```

Esse comando gera a documentação completa do projeto e a abre automaticamente no seu navegador. A partir daí, você pode explorar todos os exemplos de gerenciamento de memória e entender como o Rust implementa esses conceitos na prática.

## Referências 📑

- [Rust Documentation](https://doc.rust-lang.org/)
- [Rust Book](https://doc.rust-lang.org/book/)

