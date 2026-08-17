# Versionamento Semântico (v1.1.0)

O **Versionamento Semântico**, também conhecido como **Semantic Versioning (SemVer)**, é um padrão utilizado para identificar versões de um software de forma organizada.

As versões seguem o formato:

```text
MAJOR.MINOR.PATCH
```

Exemplo:

```text
1.2.3
```

Onde cada número possui um significado específico.

## MAJOR

O número **MAJOR** deve ser incrementado quando são feitas alterações que quebram a compatibilidade com versões anteriores do software.

Exemplo:

```text
1.5.2 -> 2.0.0
```

Isso pode acontecer quando uma funcionalidade existente é removida ou modificada de forma incompatível.

## MINOR

O número **MINOR** deve ser incrementado quando uma nova funcionalidade é adicionada, mas mantendo compatibilidade com a versão anterior.

Exemplo:

```text
1.2.0 -> 1.3.0
```

Um exemplo seria adicionar uma nova funcionalidade ou recurso ao sistema sem afetar as funcionalidades existentes.

## PATCH

O número **PATCH** deve ser incrementado quando são realizadas correções de bugs ou pequenos ajustes que não alteram as funcionalidades existentes.

Exemplo:

```text
1.2.3 -> 1.2.4
```

## Resumo

* **MAJOR:** alterações incompatíveis com versões anteriores.
* **MINOR:** novas funcionalidades compatíveis com versões anteriores.
* **PATCH:** correções de bugs e pequenos ajustes.

Por exemplo, considerando a versão:

```text
2.4.1
```

* `2` representa a versão **MAJOR**;
* `4` representa a versão **MINOR**;
* `1` representa a versão **PATCH**.
