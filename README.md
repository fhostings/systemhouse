["System House NEW"] = {
    ["Após hitar o marker"] = {
        ["Fora da casa"] = {
            ["Já vendida"] = {
                ["Player"] = {
                    ["Dono da casa"] = {
                        "Entrar", (GOLF ✔️)
                        "Editar", (GOLF ✔️)
                        "Trancar/destrancar", --Caso o ela estiver trancada vai aparecer destrancar etc e mudar o icone qnd ela tiver trancada/destrancada (GOLF ✔️)
                        "Bater na porta", (GOLF ✔️)
                        "Tocar campainha", (GOLF ✔️)
                    },
                    ["Sem ser dono da casa"] = {
                        "Bater na porta", (GOLF ✔️)
                        "Entrar", (GOLF ✔️)
                        "Tocar campainha", (GOLF ✔️)
                    },
                },
                ["Admin"] = {
                    ["Dono da casa"] = {
                        "Deletar casa", (GOLF ✔️)
                        "Ver ID", (GOLF ✔️)
                        "Duplicar interior", (GOLF ✔️)
                        "Resetar interior", (GOLF ✔️)
                        "Entrar", (GOLF ✔️)
                        "Editar", (GOLF ✔️)
                        "Trancar/destrancar", --Caso o ela estiver trancada vai aparecer destrancar etc e mudar o icone qnd ela tiver trancada/destrancada (GOLF ✔️)
                        "Bater na porta",
                        "Tocar campainha",
                    },
                    ["Sem ser dono da casa"] = {
                        "Deletar casa", (GOLF ✔️)
                        "Ver ID", (GOLF ✔️)
                        "Duplicar interior", (GOLF ✔️)
                        "Resetar interior", (GOLF ✔️)
                        "Bater na porta", (GOLF ✔️)
                        "Entrar", (GOLF ✔️)
                        "Tocar campainha", (GOLF ✔️)
                    },
                },
            },
            ["Não vendida"] = {
                ["Player"] = {
                    "Comprar casa", (GOLF ✔️)
                    ["Ao clicar no botão de comprar"] = {
                        "Comprar com moeda especial", (GOLF ✔️)
                        "Dinheiro da mão", (GOLF ✔️)
                        "Dinheiro do banco" (GOLF ✔️)
                    },
                    ["Informações da casa"] = {
                        "Tamanho", (GOLF ✔️)
                        "Nome da casa", (GOLF ✔️)
                        "ID da casa" (GOLF ✔️)
                    },
                },
                ["Admin"] = {
                    "Deletar casa", (GOLF ✔️)
                    "Ver ID", (GOLF ✔️)
                    "Comprar casa", (GOLF ✔️)
                    ["Ao clicar no botão de comprar"] = {
                        "Comprar com moeda especial", (GOLF ✔️)
                        "Dinheiro da mão", (GOLF ✔️)
                        "Dinheiro do banco" (GOLF ✔️)
                    },
                    ["Informações da casa"] = {
                        "Tamanho", (GOLF ✔️)
                        "Nome da casa", (GOLF ✔️)
                        "ID da casa" (GOLF ✔️)
                    },
                },
            },
        },
        ["Dentro da casa"] = {
            ["Player"] = {
                ["Dono da casa"] = {
                    "Sair",
                    "Editar",
                    "Trancar/destrancar", --Caso o ela estiver trancada vai aparecer destrancar etc e mudar o icone qnd ela tiver trancada/destrancada
                    "Acender a luz/apagar", --Caso ela esteja com a luz acesa ter a opção para apagar e mudar o icone qnd ela estiver acesa/apagada
                    "Bater na porta",
                    "Autorizar amigo entrar na casa",
                },
                ["Sem ser dono da casa"] = {
                    "Bater na porta",
                    "Sair",
                },
                ["Ao clicar na TV"] = {
                    "Colocar um filme pré definido",
                    "Dar play no filme",
                    "Desligar TV", --Aparecer só caso esteja tendo algo na TV
                    "Fechar menu",
                    "Botão para acessar youtube",
                    ["Aba do youtube"] = {
                        "Reproduzir na TV",
                        "Fechar",
                    },
                },
                ["Ao clicar no rádio"] = {
                    "Colocar uma música pré definida",
                    "Dar play na música",
                    "Desligar Rádio", --Aparecer só caso esteja tendo algo no rádio
                    "Fechar menu",
                    "Botão para pesquisar música",
                    ["Aba de pesquisar música"] = {
                        "Listagem de músicas",
                        "Pesquisas de músicas",
                        "Reproduzir no rádio",
                        "Fechar",
                    },
                },
                ["Ao clicar no cofre"] = {
                    ["Dono da casa"] = {
                        ["Primeira vez"] = {
                            "Digitar uma senha no cofre para deixar salvo",
                        },
                        ["Outras vezes"] = { --Abrir o cofre e mostrar os itens dentro e etyc
                            "Digitar senha do cofre",
                            "Alterar senha do cofre",
                        },
                    },
                    ["Player"] = {
                        ["Primeira vez"] = {
                        },
                        ["Outras vezes"] = { --Abrir o cofre e mostrar os itens dentro e etyc
                            "Digitar senha do cofre",
                        },
                    },
                },
                ["Ao clicar na cama"] = {
                    ["Dono da casa"] = {
                        "Deitar na cama",
                        "Dormir",
                        "Fazer sexo",
                        ["Aba de fazer sexo"] = {
                            "Um lugar para ele inserir a pessoa para fazer sexo",
                        },
                    },
                },
            },
            ["Admin"] = {
                ["Dono da casa"] = {
                    "Deletar casa",
                    "Ver ID",
                    "Duplicar interior",
                    "Resetar interior",
                    "Sair",
                    "Editar",
                    "Trancar/destrancar", --Caso o ela estiver trancada vai aparecer destrancar etc e mudar o icone qnd ela tiver trancada/destrancada
                    "Acender a luz/apagar", --Caso ela esteja com a luz acesa ter a opção para apagar e mudar o icone qnd ela estiver acesa/apagada
                    "Bater na porta",
                },
                ["Sem ser dono da casa"] = {
                    "Deletar casa",
                    "Ver ID",
                    "Duplicar interior",
                    "Resetar interior",
                    "Bater na porta",
                    "Sair",
                },
            },
        },
        ["Dentro da casa, porta dos comodos"] = {
            ["Dono da casa"] = {
                "Trancar porta",
            },
            ["Sem ser dono da casa"] = {
            },
        },
    },
    ["Imobiliária"] = {
        "Listagem de todas casas não vendidas",
        ["Ao clicar na casa não vendida"] = {
            "Mostrar o local dela" --Clicar para ver na tela da pessoa, em 360º
            "Marcar ela no mapa",
        },
        "Botão para listar suas próprias casa", --Irá listar suas próprias casas
        "Botão para vender casa",
        ["Aba de vender casa"] = {
            "Vender para player",
            "Vender para imobiliária", --Depois disso, ter uma confirmação de venda
            ["Vender para player"] = {
                "Inserir o ID", --Depois disso, ter uma confirmação de venda
            },
        },
    },
    ["Pagamento de IPTU"] = {
        "Listagem de todas suas casas, falando se está vencido o IPTU etc",
        "Um botão para detalhes",
        ["Botão de detalhes"] = {
            "Pagar IPTU", --Se o IPTU tiver vencido esse botão para pagar,
            "Listagem de detalhes da casa, como nome, tamanho, proprietário, id da casa, preço dela",
        },
    },
    ["Modo edição"] = {
        ["Inicial"] = {
            "Introdução", -- Quando for a primeira vez, ter introdução de como mexer etc... Um tutorial em escrito.
            ["Botões no centro da tela, superior"] = { --Os botões pode ser introduzidos com ícones
                "Ativar/desativar grade",
                "Acender/apagar luz",
                "Testar interior",
                "Ativar/desativar música",
                "Ativar/desativar sons",
                "Salvar interior",
                "Sair sem salvar",
            },
            ["Modo teste"] = {
                "Voltar no modo edição",
                "Acender/apagar a luz",
            }
            "Botões para acessar aba dos comodoes e etc",
            ["Mini hud"] = {
                "Saldo da mão",
                "Saldo do banco",
                "Moeda especial",
            }
            "Uma mini hud a onde mostra o saldo dele da mão, do banco e a moeda especial",
            "Em cada textura/móveis, mostrar se é com dinheiro ou moeda especial que compra",
            ["Quando salvar"] = {
                ["Perguntar"] = {
                    "Pagar com money da mão",
                    "Pagar com money do banco",
                },
            },
        },
        ["Quando clica no objeto"] = {
            "Rotacionar",
            "Mover pros lados",
            "Mover para cima e para baixo",
            "Deletar",
            "Alinhar no chão",
            ["Sub menu de rotacionar"] = {
                "Voltar",
                "Mover",
            },
        },
    },
}
