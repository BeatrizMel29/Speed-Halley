                                -Este arquivo deve registrar, de forma objetiva, o andamento semanal do projeto. A equipe não deve apagar registros anteriores. Caso o planejamento mude, a alteração deve ser descrita e justificada.



# Semana 1 — 16/09/2026 a 22/09/2026

## Planejado

- Definir a arquitetura geral da pista.
- Projetar o circuito.
- Elaborar o primeiro diagrama elétrico.
- Criar a estrutura inicial do repositório.

## Concluído

- Repositório organizado com `README.md`, `PLANEJAMENTO.md` e `PROGRESSO.md`.

## Não concluído
- Definir a arquitetura geral da pista.
- Projetar o circuito.
- Elaborar o primeiro diagrama elétrico.


## Problemas ou impedimentos



## Decisões técnicas da semana

- A equipe decidiu comparar duas opções de detecção da passagem do carrinho;
.

## Testes realizados

| Teste | Resultado |
|---|---|
| Alimentação do ESP32 em bancada | Funcionamento normal |
| Teste individual dos motores | Ambos funcionaram |

## Próximas ações

Aprimorar o circuito escolhido;
Pesquisar melhores componentes

# Semana 2 — 23/09/2026 a 29/09/2026

## Planejado

- Revisar os requisitos da competição.
- Organizar as tarefas da equipe.
- Preparar os primeiros testes eletrônicos e de comunicação

## Concluído

- Preparação das atividades para o início dos testes após a chegada dos componentes.

## Não concluído

- Montagem prática dos componentes.
- Definição da arquitetura da pista.
- Elaboração do diagrama elétrico.
- Realização dos testes práticos planejados.


## Problemas ou impedimentos

 - Os componentes ainda não estavam disponíveis, impedindo o avanço esperado na montagem e nos testes.

## Decisões técnicas da semana

- Adiar os testes que dependiam dos componentes até que os materiais fossem disponibilizados.

## Testes realizados
Não foram registrados testes práticos nesta semana devido à ausência dos componentes.

| Teste | Resultado |
|---|---|
| ____________________ | ____________________ |

## Próximas ações

- ____________________
- ____________________

---

# Semana 3 — 30/09/2026 a 06/10/2026

## Planejado

- Primeiro contato com RaspberryPi 3.
- Testar a alimentação do ESP32.
- Iniciar os testes de comunicação.

## Concluído

- Teste de alimentação do ESP32 em bancada, com funcionamento normal.
- Instalação do sistema operacional, broker MQTT, e servidor NodeRed do Raspberry

## Não concluído

- Definição completa da arquitetura da pista.
- Elaboração do diagrama elétrico.
- Integração dos componentes no sistema.

## Problemas ou impedimentos

- Ausência dos componentes e necessidade de avançar gradualmente nos testes.

## Decisões técnicas da semana

Realizar testes individuais antes de avançar para a integração dos componentes

## Testes realizados


| Teste | Resultado |
|---|---|
| Teste de alimentação do ESP32 em bancada. | deu certo|

## Próximas ações

- ____________________

---

# Semana 4 — 07/10/2026 a 13/10/2026

## Planejado

- Avançar nos testes de comunicação.
- Utilizar Wi-Fi, MQTT e Node-RED.
- Investigar dificuldades de integração.
- Registrar os resultados dos testes.

## Concluído
- Recebimento dos microcontroladores definitivos e soldagem dos ESP32C3
- Desenvolvimento e utilização de código para testes de comunicação.
- Registro visual de mensagens numéricas no Node-RED.

## Não concluído

- Definição definitiva da arquitetura da pista
- Diagrama elétrico

## Problemas ou impedimentos

- Ausência dos sensores.

## Decisões técnicas da semana

Continuar os testes de comunicação e verificar o funcionamento dos dispositivos antes de avançar para a integração.

## Testes realizados

| Teste | Resultado |
|---|---|
|Testes de conexão Wi-Fi. | | deu certo|
|Testes de comunicação envolvendo MQTT e Node-RED, com mensagens numéricas observadas no Node-RED. A origem das mensagens ainda precisa ser confirmada. | |deu certo|

## Próximas ações

- ____________________

---

# Semana 5 — 14/10/2026 a 16/10/2026

## Planejado

- Preparar a demonstração mínima para a Avaliação de Progresso 1.
- Revisar a documentação do repositório.
- Comparar o cronograma planejado com o desenvolvimento realizado.

## Concluído

- ____________________

## Não concluído

- ____________________

## Problemas ou impedimentos

- Comunicação não clara entre os grupos responsáveis pela pista, o que gerou falta de acesso aos componentes (raspberry e roteador) em muitas ocasiões.

## Decisões técnicas da semana

- ____________________

## Demonstração preparada para a AP1

Descrever qual subsistema ou conjunto de subsistemas será demonstrado na bancada.

## Situação geral na AP1

### Entregas concluídas

- ____________________

### Entregas parcialmente concluídas

- ____________________

### Entregas não concluídas

- ____________________

### Principais alterações em relação ao planejamento original

- ____________________

### Justificativas

- ____________________

---

# Modelo para semanas posteriores

Copiar o bloco abaixo sempre que uma nova semana for iniciada.

```markdown
# Semana X — DD/MM/AAAA a DD/MM/AAAA

## Planejado

- ...

## Concluído

- ...

## Não concluído

- ...

## Problemas ou impedimentos

- ...

## Decisões técnicas da semana

- ...

## Testes realizados

| Teste | Resultado |
|---|---|
| ... | ... |

## Próximas ações

- ...
```- Obstáculos: ____________________;


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
