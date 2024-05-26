<template>
    <!--Listagem dos contatos-->
    <div class="w-full px-2">
        <!--Item Contato-->
        <ListItem>
            João da Silva

            <template #actions>
                <button>Editar</button>
                <button>Excluir</button>               
            </template>
        </ListItem>
    </div>

    <!--Botão Adicionar-->
    <UIButton>Adicionar Contato</UIButton>
</template>