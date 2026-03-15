# 🧨 cve222 – Fork Bomb

**Atenção:** Este repositório contém um script malicioso (fork bomb) para fins **exclusivamente educacionais**.  
Não execute em seu computador principal ou em qualquer sistema sem proteção adequada. Use apenas em máquinas virtuais isoladas.

## 📜 Sobre o Projeto

Este é um fork bomb clássico combinado com auto-replicação, desenvolvido para estudo de técnicas de negação de serviço (DoS) e comportamento de malware em ambientes controlados.

O script:
- Cria cópias de si mesmo na pasta `Downloads` do usuário.
- Executa um fork bomb (`%0|%0`) que consome toda a CPU e RAM.
- Pode travar o sistema rapidamente.

> ⚠️ **Isso é extremamente perigoso!** Pode causar perda de dados não salvos e danos ao sistema operacional.

## 🛡️ Como testar com segurança

1. **Use uma máquina virtual** (VirtualBox, VMware, etc.) com um snapshot antes do teste.
2. Certifique-se de que não há arquivos importantes na VM.
3. Execute o script e observe o comportamento.
4. Após o teste, restaure o snapshot ou desligue a VM.

## 📌 Avisos importantes

- **NÃO EXECUTE** em seu computador pessoal, no trabalho, ou em qualquer sistema que você **NÃO** possa perder.
- O autor não se responsabiliza por danos causados pelo uso inadequado deste código.
- Este material é apenas para aprendizado sobre segurança cibernética e técnicas de malware.
- Ao baixar, você assume toda a responsabilidade pelo uso.

## 📄 Licença

Este projeto está licenciado sob a MIT License – veja o arquivo [LICENSE](LICENSE) para detalhes.  
**Use de forma ética e responsável.**

---

### 🇺🇸 English

This is an **educational fork bomb** repository. **Do not run on real hardware!** Only in isolated virtual machines.  
The script replicates itself and consumes all system resources. Use responsibly.

- Author is not liable for any damage.
- For educational purposes only.
