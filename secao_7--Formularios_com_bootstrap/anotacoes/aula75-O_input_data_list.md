# Datalist
- **Datalist** é um select, porém com busca;
- Então você pode **inserir as opções e também encontrar alguma** que está cadastrada;
- Temos um componenteno Bootstrap para est input;

o código:
~~~html
     <!-- Outros elementos -->
      <div class="col-4 m-4">
        <h2>Outros inputs</h2>
        <form>
            <!-- Data list -->
             <div class="mb-4">
                <label for="cidades" class="form-label">Selecione uma cidade</label>
                <input class="form-control" list="datalistOptions" id="cidades" placeholder="Busque a sua cidade....">
                <datalist id="datalistOptions">
                    <option value="São Paulo">
                    <option value="Belém">
                    <option value="Rio de Janeiro">
                    <option value="Belo Horizonte">
                </datalist>
             </div>
        </form>
      </div>
~~~