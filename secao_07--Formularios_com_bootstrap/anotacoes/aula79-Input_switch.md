# Switch
- O **switch** é um checkbox;
- Porém eleltem uma **estilização diferent**;
- **Parecendo um botão  de "on/off"**, bem interessante para aplicações modernas;

No código
~~~html
            <!-- Switch -->
            <div class="mb-4">
                <h2>Escolha suas configurações</h2>
                <div class="form-check form-switch">
                    <input type="checkbox" class="form-check-input" id="flex-switch">
                    <label for="flex-switch" class="form-check-label">Vocẽ quer ativar isto?</label>
                </div>
                <!-- disbled -->
                <div class="form-check form-switch">
                    <input type="checkbox" class="form-check-input" id="flex-switch" disabled>
                    <label for="flex-switch" class="form-check-label">Switch desabilitado</label>
                </div>
            </div>
~~~