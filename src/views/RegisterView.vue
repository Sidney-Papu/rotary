<template>
    <div>
        <h1>
            Cadastro de Paciente
        </h1>
        <div class="container-fluid">
            <form action="">
                <div class="row spaceCont">
                    <div class="col-12">
                        <label for="tNome" class="textoAlign">Nome:</label>
                        <input type="text" class="form-control" id="tNome" required placeholder="Digite o Nome:">
                    </div>
                </div>
                <div class="row spaceCont">
                    <div class="col-12">
                        <label for="tEndereço" class="textoAlign">Endereço:</label>
                        <input type="text" class="form-control" id="tEndereço" required
                            placeholder="Digite o Endereço:">
                    </div>
                </div>
                <div class="row spaceCont">
                    <div class="col-12">
                        <label for="tEmail" class="textoAlign">Email:</label>
                        <input type="Email" class="form-control" id="tEmail" required placeholder="Digite o Email:">
                    </div>
                </div>
                <div class="row spaceCont">
                    <div class="col-4">
                        <label for="tTelefone" class="textoAlign">Telefone:</label>
                        <input type="tel" class="form-control" id="tTelefone" required placeholder="Digite o Telefone:">
                    </div>
                    <div class="col-4">
                        <label for="tCpf" class="textoAlign">Cpf:</label>
                        <input type="text" class="form-control" id="tCpf" required placeholder="Digite o Cpf:">
                    </div>
                    <div class="col-4">
                        <label for="tRg" class="textoAlign">Rg:</label>
                        <input type="text" class="form-control" id="Rg" required placeholder="Digite o Rg:">
                    </div>
                </div>

                <div class="row">
                    <div class="col-12">
                        <label for="tDescricao">Descrição</label>
                        <textarea name="" id="tDescricao" cols="30" rows="6" class="form-control"
                            maxlength="250"></textarea>
                    </div>
                </div>
                <div class="row spaceCont">
                    <div class="col-12">
                        <input type="submit" value="Enviar" class="btn btn-primary spaceCont">
                        <input type="reset" value="Cancelar" class="btn btn-danger spaceCont">
                    </div>
                </div>

            </form>
        </div>
    </div>
</template>

<style>
.spaceCont {
    margin: 10px !important;
}
</style>