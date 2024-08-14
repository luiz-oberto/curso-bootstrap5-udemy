# Checkbox e Radioo button
- Outros inputs bem conhecidos são:
    - **Checkbox**: onde podemos  selecionar mais de uma opção;
    - **Radio**: selecionamos apenas uma opção;
- Temos componentes de Bootstrap para estes também;

No código:
~~~html
             <!-- Checkbox -->
             <div class="mb-4">
                <h2>Marque as opções</h2>
                <div class="form-check">
                    <input type="checkbox" class="form-check-input" id="privacidade">
                    <label for="privacidade" class="form-check-label">Aceitar termos de privacidade</label>
                </div>
                <!-- input já marcado -->
                <div class="form-check">
                    <input type="checkbox" class="form-check-input" id="emails" checked>
                    <label for="emails" class="form-check-label">Quer receber os e-mails de propaganda</label>
                </div>
                <!-- input desabilitado -->
                <div class="form-check">
                    <input type="checkbox" class="form-check-input" id="desabilitado" disabled checked>
                    <label for="desabilitado" class="form-check-label">Este você não vai marcar</label>
                </div>
             </div>
             <!-- Radio button -->
              <div class="mb-4">
                <h2>Qual você que?</h2>
                <div class="form-check">
                    <input type="radio" class="form-check-input" name="meu_radio" id="a" value="a" checked>
                    <label for="a" class="form-check-label">Radio checado</label>
                </div>
                <div class="form-check">
                    <input type="radio" class="form-check-input" name="meu_radio" id="b" value="b">
                    <label for="b" class="form-check-label">Radio para marcar</label>
                </div>
                <div class="form-check">
                    <input type="radio" class="form-check-input" name="meu_radio" id="c" value="c" disabled>
                    <label for="c" class="form-check-label">Radio desabilitado</label>
                </div>
              </div>
~~~