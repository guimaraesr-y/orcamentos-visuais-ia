<p align="center"><img src="assets/icon.svg" width="128" alt="Ícone Orçamentos Visuais com IA"></p>

# Orçamentos Visuais com IA

**Do áudio do cliente a um orçamento profissional — com revisão humana.**

Skill open source para ChatGPT e assistentes compatíveis que transforma briefings, mensagens ou transcrições em propostas comerciais visuais, organizadas e personalizadas.

> A skill não inventa valores, prazos, condições nem promete resultados. Cada orçamento precisa da sua revisão.

## O que faz
- Extrai escopo e entregáveis do briefing.
- Separa informações confirmadas de lacunas.
- Pergunta o que realmente altera preço e prazo.
- Produz documentos comerciais com identidade visual, quando o ambiente permite.
- Revisa inconsistências e sugere uma mensagem curta de envio.

## Experimente

1. Copie o briefing ou transcreva o áudio do cliente (não inclua dados pessoais desnecessários).
2. Ative a skill e peça: `Transforme este briefing em uma proposta visual para revisar.`
3. Confira as pendências, complete valores reais e revise antes de enviar.

## Instalação com ajuda do ChatGPT

Copie e cole este texto no ChatGPT ou em um assistente com acesso a GitHub e instalação de skills:

```text
Quero usar a skill open source "Orçamentos Visuais com IA":
https://github.com/guimaraesr-y/orcamentos-visuais-ia

1. Consulte o README e o arquivo skills/orcamentos-visuais-ia/SKILL.md do repositório.
2. Se você tiver ferramentas e permissões para instalar skills ou plugins neste ambiente, baixe o repositório, revise os arquivos e instale a skill seguindo as instruções e as regras deste ambiente. Peça minha confirmação antes de instalar ou alterar configurações.
3. Se não tiver acesso a instalação, não afirme que instalou. Mostre como adicionar a skill manualmente ou me ajude a usar as instruções copiando o SKILL.md.
4. Ao final, confirme o que realmente foi instalado e onde; mostre um teste com briefing fictício, sem inventar preço ou prazo.
```

**Importante:** colar um prompt não garante instalação automática. Isso depende de recursos, conectores e permissões do ambiente. Uma skill por arquivo não é necessariamente um plugin de um clique na loja do ChatGPT.

### Instalação manual para agentes que suportam skills locais

Baixe o repositório e copie a pasta `skills/orcamentos-visuais-ia` para o diretório de skills reconhecido pelo seu agente, conforme a documentação dele. Reinicie/recarregue skills, se necessário. Não há script executável ou requisito de credenciais.

Para ChatGPT sem suporte a instalação de skill local, use as instruções de `SKILL.md` no seu projeto ou nas instruções personalizadas, quando aplicável.

## Arquivos
- [Skill](skills/orcamentos-visuais-ia/SKILL.md)
- [Biblioteca de prompts](skills/orcamentos-visuais-ia/references/prompts.md)
- [Modelo de proposta](skills/orcamentos-visuais-ia/references/modelo-proposta.md)
- [Checklist de revisão](skills/orcamentos-visuais-ia/references/checklist.md)
- [Prompt de instalação assistida](docs/instalacao-assistida.md)
- [Ícone SVG](assets/icon.svg)

## Privacidade
Evite compartilhar CPF, dados bancários, dados clínicos e informações identificáveis de terceiros. Use exemplos fictícios ou anonimizados, com revisão humana e observância da LGPD.

## Licença
MIT. Criado por Ryan Guimarães.
