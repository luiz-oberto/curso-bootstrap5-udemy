# Arquivos
- O **input de arquivos** temuma forma diferente de receber CSS, o que torna a vida dos devs mais difícil;
- Mas a notícia boa é que o Bootstrap tem um componente para isso;
- Deixando o **input de file mais bonito**;

~~~html
    <!-- Input de aruivos -->
     <div class="col-4 m-4">
        <h2>Teste e input de arquivo</h2>
        <form>
            <div class="mb-4">
                <label for="foto" class="form-label">Apenas um arquivo:</label>
                <input type="file" class="form-control" id="foto">
            </div>
            <div class="mb-4">
                <label for="fotos" class="form-label">Múltiplos arquivos:</label>
                <input type="file" class="form-control" id="fotos" multiple>
            </div>
            <div class="mb-4">
                <label for="fotos" class="form-label">Input file desabilitado:</label>
                <input type="file" class="form-control" id="fotos2" disabled>
            </div>
        </form>
     </div>
~~~