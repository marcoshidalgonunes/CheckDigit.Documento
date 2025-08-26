# CheckDigit.Documento

Biblioteca .NET para validação e cálculo de dígitos verificadores de documentos brasileiros.

## Recursos

- Validação de CPF e CNPJ
- Cálculo de dígitos verificadores
- API simples e intuitiva

## Instalação

Via NuGet Package Manager:

```
Install-Package CheckDigit.Documento
```

Ou via .NET CLI:

```
dotnet add package CheckDigit.Documento
```

## Uso

```csharp
using CheckDigit.Documento;

// Validação de CPF
bool valido = DocumentoValidator.ValidarCPF("12345678909");

// Validação de CNPJ
bool validoCnpj = DocumentoValidator.ValidarCNPJ("12345678000195");
```

## Documentação e Licença

Veja este [GitHub](https://github.com/marcoshidalgonunes/CheckDigit.Documento) para a documentação completa, com exemplos e licenciamento desta biblioteca.
