# 🔐 Projeto: IAM no Azure (100% No-Code)

Este projeto demonstra como implementar boas práticas de **Identity and Access Management (IAM)** em um ambiente simulado no Microsoft Azure, utilizando **apenas o portal (sem código ou scripts)**.

O objetivo é mostrar como aplicar **controle de acesso seguro**, segmentação por funções (RBAC), autenticação multifator (MFA) e políticas de acesso condicional em uma infraestrutura simples e realista.

---

## 🧱 Estrutura do Projeto

- Criação de **Resource Group** e **Storage Account**
- Criação de **grupos e usuários** no Azure Active Directory (Azure AD)
- Atribuição de **permissões com RBAC**
- Configuração de **MFA para administradores**
- Aplicação de uma **política de acesso condicional**

---

## 📷 Prints de Tela

As capturas de tela de cada etapa estão na pasta [`/prints`](./prints) para facilitar o entendimento de como o ambiente foi configurado.

---

## 📝 Etapas Realizadas

1. **Criação do Resource Group** chamado `RG-IAM-Projeto`
2. **Criação de um Storage Account** chamado `iamprojetostorage`
3. **Criação de grupos** no Azure AD:
   - `IAM-Admins` (administradores)
   - `IAM-Devs` (desenvolvedores)
4. **Criação de usuários de teste**
5. **Atribuição de permissões com RBAC**:
   - `IAM-Admins`: Contribuidor
   - `IAM-Devs`: Leitor
6. **Configuração de MFA** para o grupo `IAM-Admins`
7. **Criação de uma política de acesso condicional** exigindo MFA para administradores

---

## 💡 Tecnologias Utilizadas

- Microsoft Azure Portal
- Azure Active Directory (AAD)
- IAM (Identity and Access Management)
- RBAC (Role-Based Access Control)
- MFA (Multi-Factor Authentication)
- Políticas de Acesso Condicional

---

## 👤 Autor

**André Branco**  
Estudante de Cibersegurança com foco em **Identity and Access Management no Azure**  
[LinkedIn](https://www.linkedin.com/in/andrebranco13/)

---

## 📌 Observação

Este projeto foi desenvolvido com foco educacional e para demonstrar conhecimento prático em Azure IAM, especialmente para quem está iniciando na área de segurança em nuvem.

