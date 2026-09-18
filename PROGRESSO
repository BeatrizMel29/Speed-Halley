# Projeto Integrador — Competição de Carrinhos

#SpeedHalley 

**Nome da equipe: Speed-Halley
**Turma: Mecatrônica 3M  
**Professor técnico: Filipe Lins

### Integrantes e áreas de atuação

| Integrante | Área principal | Responsabilidades |
|---|---|---|
| Micael | Calibração | calibração e operação |
| Jullya Witoria | Mecânica | Montagem, preparação e obstáculos |
| Sara Beatriz  | Projeto e documentação | Arquitetura, desenhos, organização da documentação |
| Beatriz Melquíades | Eletrônica e integração elétrica | Alimentação, sensores e conexões |
| Rayssa Beatriz | Software e controle | programação, comunicação, integração |

---

## 1. Objetivo do projeto

Desenvolver uma pista automatizada para veículo terrestre em pequena escala para participação na Competição de Carrinhos do Projeto Integrador.
---

## 2. Conceito da solução

Descrever, de forma objetiva, a solução escolhida pela equipe.

Exemplo:

- Cronometragem: ________________;
- Comunicação enre os microcontroladores: ____________________;
- Circuito e sensores: ____________________;
- Alimentação: ____________________;
- Automatização: ____________________;
- Obstáculos: ____________________;


---

## 3. Arquitetura geral

Inserir aqui um diagrama da arquitetura do sistema ou um link para o arquivo correspondente em `docs/arquitetura/`.


### Subsistemas

- **Mecânica: descrever resumidamente.
- **Eletrônica:** descrever resumidamente.
- **Software:** descrever resumidamente.
- **Comunicação:** descrever resumidamente.
- **Alimentação:** descrever resumidamente.

---

## 4. Estado atual do desenvolvimento

Atualizar esta seção ao longo do projeto.

### Concluído

- [ ] Definição da arquitetura geral
- [ ] Projeto mecânico inicial
- [ ] Diagrama elétrico inicial
- [ ] Comunicação com o sistema da organização
- [ ] Controle dos motores em bancada
- [ ] Integração mecânica
- [ ] Integração eletroeletrônica
- [ ] Teste do veículo em movimento
- [ ] Integração da câmera
- [ ] Outros: ____________________

### Em desenvolvimento

Definir o método de detecção e cronometragem;
Definir a programação dos microcontroladores;
Definir o circuito;


### Pendências principais

Definir o método de detecção e cronometragem;
Definir a programação dos microcontroladores;
Definir o circuito;
Software e integração enre os componentes.


## 5. Planejamento

O planejamento semanal da equipe está disponível em:

[`PLANEJAMENTO.md`](PLANEJAMENTO.md)

O registro semanal de atividades está disponível em:

[`PROGRESSO.md`](PROGRESSO.md)

---

## 6. Documentação técnica

Organizar a documentação técnica, preferencialmente, nas seguintes pastas:

```text
docs/
├── arquitetura/
├── mecanica/
├── eletronica/
├── software/
└── testes/
```

### Documentos disponíveis

- Arquitetura geral: ____________________
- Projeto mecânico: ____________________
- Diagrama elétrico: ____________________
- Documentação do software: ____________________
- Lista de materiais: ____________________
- Registros de testes: ____________________

---

## 7. Materiais e componentes

| Item | Quantidade | Origem | Situação |
|---|---:|---|---|
| ESP32 | 1 | Kit da organização | Disponível |
| Motor DC | 2 | Kit da organização | Disponível |
| Driver de motor | 1 | Kit da organização | Disponível |
| ____________________ | ___ | Equipe / organização | ____________________ |

---

## 8. Comunicação com a organização

### Comandos

- Protocolo: UDP unicast
- Porta: 5000
- Formato: JSON em UTF-8
- Frequência nominal: 60 Hz

Formato esperado:

```json
{
  "sequencia": 123,
  "volante": 0,
  "aceleracao": 0,
  "habilitado": true
}
```

### Telemetria

- Protocolo: MQTT 3.1.1 sobre TCP
- Porta: 1883
- Tópico previsto: `carrinhos/<equipe>/telemetria`

Os campos definitivos de telemetria serão definidos pela equipe em conjunto com os professores.

---

## 9. Testes realizados

Registrar os testes relevantes do projeto. Para registros mais detalhados, utilizar `docs/testes/`.

| Data | Teste | Resultado | Próxima ação |
|---|---|---|---|
| __/__/2026 | ____________________ | ____________________ | ____________________ |

---

## 10. Observações

Registrar aqui informações importantes que não se encaixem nas demais seções. 
