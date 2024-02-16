# Azure Linguagem Natural
Projeto da aula Linguagem Natural Azure AI services

## Criando um recurso de fala do Azure AI

1. Acessar o Speech Studio no endereço https://speech.microsoft.com/portal;
2. Logar na conta na opção Sign in;
3. Clicar no íncone de Configurações (engrenagem);
4. Na guia de Resoucers, clica na opção + Create a new resource;
5. Preencha o formulário:
- Name of new resource: linguagemnatural
- Subscription: Azure Subscription 1
- Region: East US
- Princing Tier: Free F0
- Resource group: laboratorio_dio
>> Create resource
6. Sewlecionar ao lado no nome do recurso criado;
>> Use resource
7. Selecionar a opção Real-time speech to text;
8. Caixa de texto ao lado de Iacknowledge that this application uses the resource linguagemnatural and will incur usage to my account: selecionada
9. Em Choose a language, seleionar a opção Portuguese (Brazil)
10. Selecionar o arquivo na opção Browse files no quadro Drag and drop audio file(s) here or;
11. Resultado obtido: Áudio gravado para teste no lengu Studio no azul. 
12. Json obtido: 
```
[
    {
        "Id": "047a6b17618848c7bb826476af6cc5a1",
        "RecognitionStatus": 0,
        "Offset": 6700000,
        "Duration": 42400000,
        "Channel": 0,
        "DisplayText": "Áudio gravado para teste no lengu Studio no azul.",
        "NBest": [
            {
                "Confidence": 0.64728093,
                "Lexical": "áudio gravado para teste no lengu studio no azul",
                "ITN": "áudio gravado para teste no lengu studio no azul",
                "MaskedITN": "áudio gravado para teste no lengu studio no azul",
                "Display": "Áudio gravado para teste no lengu Studio no azul.",
                "Words": [
                    {
                        "Word": "áudio",
                        "Offset": 6700000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "gravado",
                        "Offset": 9500000,
                        "Duration": 8800000
                    },
                    {
                        "Word": "para",
                        "Offset": 19900000,
                        "Duration": 3200000
                    },
                    {
                        "Word": "teste",
                        "Offset": 23100000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "no",
                        "Offset": 29100000,
                        "Duration": 2400000
                    },
                    {
                        "Word": "lengu",
                        "Offset": 31500000,
                        "Duration": 3600000
                    },
                    {
                        "Word": "studio",
                        "Offset": 35100000,
                        "Duration": 8400000
                    },
                    {
                        "Word": "no",
                        "Offset": 43500000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "azul",
                        "Offset": 45500000,
                        "Duration": 3600000
                    }
                ]
            },
            {
                "Confidence": 0.64728093,
                "Lexical": "áudio gravado para teste no lengu studio no azul",
                "ITN": "áudio gravado para teste no lengu studio no azul",
                "MaskedITN": "áudio gravado para teste no lengu studio no azul",
                "Display": "áudio gravado para teste no lengu studio no azul",
                "Words": [
                    {
                        "Word": "áudio",
                        "Offset": 6700000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "gravado",
                        "Offset": 9500000,
                        "Duration": 8800000
                    },
                    {
                        "Word": "para",
                        "Offset": 19900000,
                        "Duration": 3200000
                    },
                    {
                        "Word": "teste",
                        "Offset": 23100000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "no",
                        "Offset": 29100000,
                        "Duration": 2400000
                    },
                    {
                        "Word": "lengu",
                        "Offset": 31500000,
                        "Duration": 3600000
                    },
                    {
                        "Word": "studio",
                        "Offset": 35100000,
                        "Duration": 8400000
                    },
                    {
                        "Word": "no",
                        "Offset": 43500000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "azul",
                        "Offset": 45500000,
                        "Duration": 3600000
                    }
                ]
            },
            {
                "Confidence": 0.64728093,
                "Lexical": "áudio gravado para teste no lengu studio no azul",
                "ITN": "áudio gravado para teste no lengu studio no azul",
                "MaskedITN": "áudio gravado para teste no lengu studio no azul",
                "Display": "áudio gravado para teste no lengu studio no azul",
                "Words": [
                    {
                        "Word": "áudio",
                        "Offset": 6700000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "gravado",
                        "Offset": 9500000,
                        "Duration": 8800000
                    },
                    {
                        "Word": "para",
                        "Offset": 19900000,
                        "Duration": 3200000
                    },
                    {
                        "Word": "teste",
                        "Offset": 23100000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "no",
                        "Offset": 29100000,
                        "Duration": 2400000
                    },
                    {
                        "Word": "lengu",
                        "Offset": 31500000,
                        "Duration": 3600000
                    },
                    {
                        "Word": "studio",
                        "Offset": 35100000,
                        "Duration": 8400000
                    },
                    {
                        "Word": "no",
                        "Offset": 43500000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "azul",
                        "Offset": 45500000,
                        "Duration": 3600000
                    }
                ]
            },
            {
                "Confidence": 0.647281,
                "Lexical": "áudio gravado para teste no lengu studio no azul",
                "ITN": "áudio gravado para teste no lengu studio no azul",
                "MaskedITN": "áudio gravado para teste no lengu studio no azul",
                "Display": "áudio gravado para teste no lengu studio no azul",
                "Words": [
                    {
                        "Word": "áudio",
                        "Offset": 6700000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "gravado",
                        "Offset": 9500000,
                        "Duration": 8800000
                    },
                    {
                        "Word": "para",
                        "Offset": 19900000,
                        "Duration": 3200000
                    },
                    {
                        "Word": "teste",
                        "Offset": 23100000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "no",
                        "Offset": 29100000,
                        "Duration": 2400000
                    },
                    {
                        "Word": "lengu",
                        "Offset": 31500000,
                        "Duration": 3600000
                    },
                    {
                        "Word": "studio",
                        "Offset": 35100000,
                        "Duration": 8400000
                    },
                    {
                        "Word": "no",
                        "Offset": 43500000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "azul",
                        "Offset": 45500000,
                        "Duration": 3600000
                    }
                ]
            },
            {
                "Confidence": 0.64728093,
                "Lexical": "áudio gravado para teste no lengu studio no azul",
                "ITN": "áudio gravado para teste no lengu studio no azul",
                "MaskedITN": "áudio gravado para teste no lengu studio no azul",
                "Display": "áudio gravado para teste no lengu studio no azul",
                "Words": [
                    {
                        "Word": "áudio",
                        "Offset": 6700000,
                        "Duration": 2800000
                    },
                    {
                        "Word": "gravado",
                        "Offset": 9500000,
                        "Duration": 8800000
                    },
                    {
                        "Word": "para",
                        "Offset": 19900000,
                        "Duration": 3200000
                    },
                    {
                        "Word": "teste",
                        "Offset": 23100000,
                        "Duration": 6000000
                    },
                    {
                        "Word": "no",
                        "Offset": 29100000,
                        "Duration": 2400000
                    },
                    {
                        "Word": "lengu",
                        "Offset": 31500000,
                        "Duration": 3600000
                    },
                    {
                        "Word": "studio",
                        "Offset": 35100000,
                        "Duration": 8400000
                    },
                    {
                        "Word": "no",
                        "Offset": 43500000,
                        "Duration": 2000000
                    },
                    {
                        "Word": "azul",
                        "Offset": 45500000,
                        "Duration": 3600000
                    }
                ]
            }
        ]
    }
]
```
Obs.: a IA não reconheceu a palavra "language" a colocando como lengu e traduziu a palavra Azure para azul.

## Análise de Sentimentos com o Language Studio
1. Acesse o portal do Azure no endereço https://portal.azure.com;
2. Clique na opção + Create a resource;
3. Clicar na opção AI + Machine Learning;
4. Selecionar a opção Language service;
5. Clicar no botão Continue to create your resource;
6. Preencher o formulário com os dados:
- Subscription: Azure Subscription 1
- Resource group: laboratorio_dio
- Region: East US
- Name: linguagemnatural2
- Pricing tier: Free F0
- By checking this box I certify that I have reviewed and acknowledge the terms in the Responsible AI Notice: Selecionado
>> Review + create<br>
7. Após finalizada a criação, clicar em Go to resource group;
8. Em uma nova guia abrir o Language Studio no endereço: https://language.cognitive.azure.com;
9. Se logar na conta em Sign in;
10. Preencher o formulário com os dados:
- Azure directory: BB
- Azure Subscription: Azure subscription 1
- Resource type: Language
- Resource name: linguagemnatural2
>> Done
11. Clicar em Create new;
12. Escolha a aba Classify text;
13. Selecione a opção Analyze sentiment and opinions;
14. Em Select text language, escolher Portuguese (Brazil);
15. Selecionar o arquivo na opção Browse for a file no quadro Drag and drop audio file(s) here or;
16. Caixa de texto ao lado de I acknowledge that running this demo will incur usage and may incur costs to my Azure resource: selecionada
>> Run
17. Resultado apresentado:
Analyzed sentiment
Document sentiment
Mixed
Confidence: 30.00%
30.00%
POSITIVE
0.00%
NEUTRAL
69.00%
NEGATIVE

Sentence sentiment 1
Positive
Confidence: 90.00%
90.00%
POSITIVE
1.00%
NEUTRAL
8.00%
NEGATIVE

Sentence sentiment 2
Neutral
Confidence: 4.00%
4.00%
POSITIVE
93.00%
NEUTRAL
3.00%
NEGATIVE

Sentence sentiment 3
Negative
Confidence: 0.00%
0.00%
POSITIVE
0.00%
NEUTRAL
100.00%
NEGATIVE

Sentence sentiment 4
Negative
Confidence: 0.00%
0.00%
POSITIVE
0.00%
NEUTRAL
100.00%
NEGATIVE

Sentence sentiment 5
Neutral
Confidence: 1.00%
1.00%
POSITIVE
99.00%
NEUTRAL
0.00%
NEGATIVE


17. JSON apresentado: 
```
{
    "documents": [
        {
            "id": "id__1763",
            "sentiment": "mixed",
            "confidenceScores": {
                "positive": 0.3,
                "neutral": 0,
                "negative": 0.69
            },
            "sentences": [
                {
                    "sentiment": "positive",
                    "confidenceScores": {
                        "positive": 0.9,
                        "neutral": 0.01,
                        "negative": 0.08
                    },
                    "offset": 0,
                    "length": 147,
                    "text": "O Busch Gardens é um parque bastante esperando por mim e pelo Adriel, que gostamos de montanhas-russas, e nem tanto pelo Daniel pelo mesmo motivo. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "neutral",
                    "confidenceScores": {
                        "positive": 0.04,
                        "neutral": 0.93,
                        "negative": 0.03
                    },
                    "offset": 147,
                    "length": 205,
                    "text": "Essa era a nossa segunda vez no parque, que não fica em Orlando e sim em Tampa, e utilizamos a mesma estratégia da viagem anterior (#orlando2017 - Dia 10 - Busch Gardens) para deslocamentos, atrações etc. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 352,
                    "length": 185,
                    "text": "Infelizmente ele não estava tão vazio como da nossa primeira vez e tivemos que enfrentar algumas filas (especialmente na Tigris, montanha-russa muito louca e recém-inaugurada à época). ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 537,
                    "length": 91,
                    "text": "Por outro lado, não estava tão quente quanto em 2017, o que diminui a sensação de cansaço. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "neutral",
                    "confidenceScores": {
                        "positive": 0.01,
                        "neutral": 0.99,
                        "negative": 0
                    },
                    "offset": 628,
                    "length": 105,
                    "text": "Para conhecer detalhes sobre o parque, acesse o link da visita anterior, que descrevemos detalhadamente.  ",
                    "targets": [],
                    "assessments": []
                }
            ],
            "warnings": []
        }
    ],
    "errors": [],
    "modelVersion": "2022-11-01"
}
```

Obs.: Apesar de a IA ter considerado o texto como negativo, ele tem um viés mais positivo.

Ref.: documento criado como projeto em treinamento da Dio e com base na documentação oficial, disponível nos endereços: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html e https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html
