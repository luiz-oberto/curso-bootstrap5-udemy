# Select
- Há **dois tipos de select**;
    - **Valor único**: usuário só pode escolher uma opção;
    - **Valores múltiplos**:  usuário pode escolher uma ou mais;;
- O Bootstrap possui componente para os dois;

no código:
~~~html
            <!-- Select -->
              <!-- uma opção -->
             <div class="mb-4">
                <label for="opcoes" class="form-label"> Seleciona a sua</label>
                <select class="form-select" name="opcoes" id="opcoes">
                    <option selected>Selcione uma opção...</option>
                    <option value="1">Primeira</option>
                    <option value="2">Segunda</option>
                    <option value="3">Terceira</option>
                </select>
             </div>
             <!-- mais de uma opção -->
             <div class="mb-4">
                <label for="opcoes" class="form-label">Selecione as suas:</label>
                <select class="form-select" multiple>
                    <option>Selecione as suas opções</option>
                    <option value="1">Maçã</option>
                    <option value="2">Banana</option>
                    <option value="3">Laranja</option>
                </select>
             </div>
             <!-- Disabled -->
             <div class="mb-4">
                <label for="opcoes" class="form-label"> Seleciona a sua</label>
                <select class="form-select" name="opcoes2" id="opcoes2" disabled>
                    <option selected>Selcione uma opção...</option>
                    <option value="1">Primeira</option>
                    <option value="2">Segunda</option>
                    <option value="3">Terceira</option>
                </select>
             </div>
~~~