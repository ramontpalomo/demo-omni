flowchart TD
    Start([Início do Processo]) --> Step1[1. Entender a vaga e a empresa]
    
    Step1 --> Decision1{Concordando?}
    
    Decision1 -->|Sim| Step2A[2.1 Formulário Typeform<br/>Perguntas qualificadoras]
    Decision1 -->|Sim| Step2B[2.2 Agente IA WhatsApp<br/>Mesmas perguntas]
    
    Step2A --> Decision2{Aprovado na<br/>qualificação?}
    Step2B --> Decision2
    
    Decision2 -->|Não| End1([Processo encerrado])
    Decision2 -->|Sim| Step3[3. Desafio Técnico<br/>Briefing - 7 dias para entrega]
    
    Step3 --> Decision3{Aprovado no<br/>desafio?}
    
    Decision3 -->|Não| End2([Processo encerrado])
    Decision3 -->|Sim| Step4[4. Entrevista com Ramon<br/>Sócio-fundador]
    
    Step4 --> Decision4{Aprovado na<br/>entrevista?}
    
    Decision4 -->|Não| End3([Processo encerrado])
    Decision4 -->|Sim| Step5[5. Verificação de Referências<br/>& Proposta]
    
    Step5 --> Decision5{Referências OK<br/>& Aceita proposta?}
    
    Decision5 -->|Não| End4([Processo encerrado])
    Decision5 -->|Sim| Step6[6. Onboarding]
    
    Step6 --> End5([Candidato integrado! 🎉])
    
    Decision1 -->|Não| End6([Processo encerrado])
    
    style Start fill:#e3f2fd
    style Step1 fill:#90caf9
    style Step2A fill:#fff59d
    style Step2B fill:#fff59d
    style Step3 fill:#a5d6a7
    style Step4 fill:#ce93d8
    style Step5 fill:#f48fb1
    style Step6 fill:#4fc3f7
    style End5 fill:#66bb6a
    style End1 fill:#ef5350
    style End2 fill:#ef5350
    style End3 fill:#ef5350
    style End4 fill:#ef5350
    style End6 fill:#ef5350
    style Decision1 fill:#ffcc80
    style Decision2 fill:#ffcc80
    style Decision3 fill:#ffcc80
    style Decision4 fill:#ffcc80
    style Decision5 fill:#ffcc80
