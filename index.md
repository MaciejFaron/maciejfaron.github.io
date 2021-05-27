## Welcome to Maciek's personal page

Nothing here right now, but that will change soon ;).

<div class="form-container">
    <form id="gmCalc" class="flex-container">
        <section class="form-left-side">
            <span id="calcTitle" class="form-h1">Kalkulator</span>
            <ul class="slider-list">
                <li class="slider-li slider-with-value-box">
                    <div class="flex-container flex-baseline">
                        <label class="form-h2" for="moneyValue">Kwota faktury Brutto</label>
                        <div>
                            <input id="moneyValue" class="value-box rounder-box" type="number" min="1000" max="100000" value="5000">
                            <label class="input-info" for="moneyValue">PLN Brutto</label>
                        </div>
                    </div>
                    <input id="moneyRange" class="slider" type="range" min="1000" max="100000" value="5000">
                    <div class="flex-container">
                        <span class="slider-info slider-min">1,000 zł</span>
                        <span class="slider-info slider-max">100,000 zł</span>
                    </div>
                </li>
                <li class="slider-li slider-with-value-box">
                    <div class="flex-container flex-baseline">
                        <label class="form-h2" for="daysValue">Dni finansowania</label>
                        <div>
                            <input id="daysValue" class="value-box rounder-box" type="number" min="1" max="60" value="14">
                            <label class="input-info" for="daysValue">Dni finansowania</label>
                        </div>    
                    </div>
                    <input id="daysRange" class="slider" type="range" min="1" max="60" value="14">
                    <div class="flex-container">
                        <span class="slider-info slider-min">1 dzień</span>
                        <span class="slider-info slider-max">60 dni</span>
                    </div>
                </li>
            </ul>
            <fieldset class="go-check-boxes">
                <div class="checkbox-container flex-container flex-baseline">
                    <p class="label-txt label-silent">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris sed gravida ex, nec eleifend mauris. Vivamus et ornare augue. Suspendisse potenti.Vivamus vitae ligula sit amet velit porta ultricies.</p>
                    <label class="label-cb" for="checkA">
                        <span class="cb-opt-a">Nie</span><input id="checkA" type="checkbox" name="name" /><i></i><span class="cb-opt-B">Tak</span>
                    </label>
                </div>
                <div class="checkbox-container flex-container flex-baseline">
                    <p class="label-txt label-silent">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris sed gravida ex, nec eleifend mauris. Vivamus et ornare augue. Suspendisse potenti.Vivamus vitae ligula sit amet velit porta ultricies.</p>
                    <label class="label-cb" for="checkB">
                        <span class="cb-opt-a">Nie</span><input id="checkB" type="checkbox" name="name" /><i></i><span class="cb-opt-B">Tak</span>
                    </label>
                </div>
            </fieldset>
        </section>
        <section class="form-right-side flex-vertical">
            <div class="column-item">
                <span class="form-amount description1">Teraz wypłacamy Tobie</span>
                <div id="amount" class="form-amount h1"></div>
            </div>
            <div class="column-item">
                <span class="form-amount description2">Koszt finansowania</span>
                <div id="comission" class="form-amount h2"></div>
            </div>
            <div class="column-item">
                <button type="submit" class="rounder-box button button-light">Finansuj fakturę</button>
                <div><a class="link link-light" href="#">Lub przejdź do negocjacji</a></div>
            </div>
        </section>
    </form>
</div>
<link rel="stylesheet" type="text/css" href="calc.css" media="screen"/>
<script src="calc.js"></script>