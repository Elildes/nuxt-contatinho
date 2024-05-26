<template>
    <!--Listagem dos contatos-->
    <div class="w-full px-2">
        <!--Item Contato
        <div class="w-full p-4 border bg-gray-200 flex items-center justify-between">
            <span class="text-xl font-semibold">João da Silva</span>

            <div class="w-32 space-x-2">
                <button>Editar</button>
                <button>Excluir</button>
            </div>
        </div> -->
        <ListItem>
            João da Silva

            <template #actions>
                <button>Editar</button>
                <button>Excluir</button>               
            </template>
        </ListItem>
    </div>

    <button class="w-full p-4 mt-8 border b-blue-200 rounded bg-blue-500 text-white flex items-center justify-center">
        Adicionar Contato
    </button>
</template>