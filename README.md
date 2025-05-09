<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Analisi dei costi distillato Santoro</title>
    <!-- Icona incorporata direttamente come SVG -->
    <link rel="icon" href="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB2aWV3Qm94PSIwIDAgNjQgNjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CiAgPCEtLSBTZm9uZG8gY2lyY29sYXJlIC0tPgogIDxjaXJjbGUgY3g9IjMyIiBjeT0iMzIiIHI9IjMwIiBmaWxsPSIjMDA1NTAwIiAvPgogIDxjaXJjbGUgY3g9IjMyIiBjeT0iMzIiIHI9IjI4IiBmaWxsPSIjZmZmZmZmIiBmaWxsLW9wYWNpdHk9IjAuMSIgLz4KICAKICA8IS0tIERpc2Vnbm8gc3RpbGl6emF0byBkaSB1biBkaXN0aWxsYXRvcmUgLS0+CiAgPHBhdGggZD0iTTI1LDE1IEwyNSwyMiBMMjAsMzYgQzE4LDQwIDE4LDQ0IDIyLDQ2IEw0Miw0NiBDNDYsNDQgNDYsNDAgNDQsMzYgTDM5LDIyIEwzOSwxNSBaIiAKICAgICAgICBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS13aWR0aD0iMiIgZmlsbD0ibm9uZSIgLz4KICAKICA8IS0tIEdvY2NlIHN0aWxpenphdGUgLS0+CiAgPGNpcmNsZSBjeD0iMzIiIGN5PSI1MCIgcj0iMiIgZmlsbD0iI2ZmZmZmZiIgLz4KICA8Y2lyY2xlIGN4PSIyNiIgY3k9IjQzIiByPSIxLjUiIGZpbGw9IiNmZmZmZmYiIC8+CiAgPGNpcmNsZSBjeD0iMzgiIGN5PSIzOSIgcj0iMS41IiBmaWxsPSIjZmZmZmZmIiAvPgogIDxjaXJjbGUgY3g9IjI5IiBjeT0iMzQiIHI9IjEiIGZpbGw9IiNmZmZmZmYiIC8+CiAgPGNpcmNsZSBjeD0iMzYiIGN5PSIzMSIgcj0iMSIgZmlsbD0iI2ZmZmZmZiIgLz4KICAKICA8IS0tIFRhcHBvIHN1cGVyaW9yZSAtLT4KICA8cmVjdCB4PSIyNCIgeT0iMTIiIHdpZHRoPSIxNiIgaGVpZ2h0PSIzIiBmaWxsPSIjZmZmZmZmIiByeD0iMSIgLz4KICAKICA8IS0tIEJhc2UgZGVsIGRpc3RpbGxhdG9yZSAtLT4KICA8cmVjdCB4PSIyMCIgeT0iNDYiIHdpZHRoPSIyNCIgaGVpZ2h0PSIyIiBmaWxsPSIjZmZmZmZmIiByeD0iMSIgLz4KICA8cGF0aCBkPSJNMjIsNDggTDQyLDQ4IEw0MCw1MiBMMjQsNTIiIGZpbGw9IiNmZmZmZmYiIC8+Cjwvc3ZnPg==" type="image/svg+xml">
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f5f5f5;
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 5px;
        }
        h1 {
            text-align: center;
            color: #005500;
            margin-bottom: 30px;
            border-bottom: 2px solid #eaeaea;
            padding-bottom: 10px;
        }
        .section {
            margin-bottom: 30px;
        }
        .input-group {
            display: flex;
            align-items: center;
            margin-bottom: 12px;
        }
        .input-group label {
            width: 280px;
            font-weight: bold;
        }
        .input-group input, .input-group select {
            width: 120px;
            padding: 8px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .input-group .unit {
            margin-left: 10px;
            color: #666;
            width: 60px;
        }
        .section-title {
            background-color: #005500;
            color: white;
            padding: 10px 15px;
            margin: 20px 0 15px 0;
            border-radius: 4px;
            font-weight: bold;
            font-size: 16px;
        }
        .results-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }
        .results-table th, .results-table td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        .results-table th {
            background-color: #f0f0f0;
            font-weight: bold;
        }
        .results-table tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        .results-table .numeric {
            text-align: right;
        }
        .results-table .highlight {
            background-color: #e6f7ff;
            font-weight: bold;
        }
        .calculate-btn {
            padding: 10px 20px;
            background-color: #005500;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
            display: block;
            margin: 20px auto;
            transition: background-color 0.3s;
        }
        .calculate-btn:hover {
            background-color: #003300;
        }
        .chart-container {
            width: 100%;
            display: flex;
            justify-content: center;
            margin: 30px 0;
        }
        .pie-chart {
            width: 350px;
            height: 350px;
        }
        .results-summary {
            background-color: #f0fff0;
            padding: 15px;
            border-radius: 4px;
            margin-top: 20px;
            border-left: 4px solid #005500;
        }
        .summary-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
        }
        .summary-item .label {
            font-weight: bold;
        }
        .profit-positive {
            color: green;
        }
        .profit-negative {
            color: red;
        }
        .two-columns {
            display: flex;
            gap: 20px;
        }
        .column {
            flex: 1;
        }
        @media (max-width: 768px) {
            .two-columns {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Analisi dei costi distillato</h1>
        
        <div class="section">
            <div class="section-title">Informazioni generali</div>
            
            <div class="two-columns">
                <div class="column">
                    <div class="input-group">
                        <label for="distillateType">Tipo di distillato:</label>
                        <select id="distillateType">
                            <option value="MANDARINO">MANDARINO</option>
                            <option value="LIMONE">LIMONE</option>
                            <option value="ARANCIA">ARANCIA</option>
                        </select>
                        <div class="unit"></div>
                    </div>
                    
                    <div class="input-group">
                        <label for="processCapacity">Capacità di lavorazione:</label>
                        <input type="number" id="processCapacity" value="4200">
                        <div class="unit">Lt/h</div>
                    </div>
                    
                    <div class="input-group">
                        <label for="distillAmount">Quantità da distillare:</label>
                        <input type="number" id="distillAmount" value="50000">
                        <div class="unit">Lt</div>
                    </div>
                </div>
                
                <div class="column">
                            <div class="input-group">
                        <label for="oilConcentration">Concentrazione di olio:</label>
                        <input type="number" id="oilConcentration" value="2.7" step="0.1">
                        <div class="unit">‰</div>
                    </div>
                    
                    <!-- Portata vapore nascosta -->
                    <input type="hidden" id="steamFlow" value="1500">
                    
                    <div class="input-group">
                        <label for="operatorMachines">Impianti per operatore:</label>
                        <input type="number" id="operatorMachines" value="1">
                        <div class="unit">n°</div>
                    </div>
                </div>
            </div>
            
            <!-- Parametri di costo nascosti -->
            <input type="hidden" id="gasPrice" value="0.42">
            <input type="hidden" id="electricityPrice" value="0.21">
            <input type="hidden" id="boilerEfficiency" value="95">
            <input type="hidden" id="laborPrice" value="30">
            <input type="hidden" id="waterPrice" value="0.001">
            <input type="hidden" id="steamPerCubicMeterGas" value="18.16">
            
            <button class="calculate-btn" onclick="calculateResults()">Calcola</button>
            
            <!-- Hidden inputs for calculations -->
            <input type="hidden" id="vacuumPumpPower" value="13">
            <input type="hidden" id="recyclingPumpsPower" value="17.46">
            <input type="hidden" id="smallPumpsPower" value="4.48">
            <input type="hidden" id="wellPumpPower" value="6">
            <input type="hidden" id="centrifugePower" value="15">
            <input type="hidden" id="tanksPower" value="1.5">
            <input type="hidden" id="waterConsumption" value="7000">
        </div>
        
        <div class="section" id="resultsSection" style="display: none;">
            <div class="section-title">Costi per ciclo</div>
            
            <div class="results-summary">
                <div class="summary-item">
                    <span class="label">Durata ciclo:</span>
                    <span id="cycleDuration">-</span>
                </div>
                <div class="summary-item">
                    <span class="label">Olio recuperato:</span>
                    <span id="recoveredOil">-</span>
                </div>
                <div class="summary-item">
                    <span class="label">Costo totale:</span>
                    <span id="totalCostSummary">-</span>
                </div>
                <div class="summary-item">
                    <span class="label">Costo per litro:</span>
                    <span id="costPerLiterSummary">-</span>
                </div>
            </div>
            
            <!-- Tabella delle voci di costo nascosta, ma manteniamo i div per gli ID -->
            <div style="display: none;">
                <span id="gasCost"></span>
                <span id="electricityCost"></span>
                <span id="laborCost"></span>
                <span id="waterCost"></span>
                <span id="totalCost"></span>
                <span id="gasPercentage"></span>
                <span id="electricityPercentage"></span>
                <span id="laborPercentage"></span>
                <span id="waterPercentage"></span>
            </div>
            
            <div class="chart-container">
                <canvas id="costPieChart" class="pie-chart"></canvas>
            </div>
            
            <div class="section-title">Analisi profitto</div>
            
            <table class="results-table">
                <tr>
                    <th>Parametro</th>
                    <th>Per litro (€/Lt)</th>
                    <th>Totale (€)</th>
                </tr>
                <tr>
                    <td>Prezzo di vendita</td>
                    <td id="sellingPricePerLiter" class="numeric">-</td>
                    <td id="totalSellingPrice" class="numeric">-</td>
                </tr>
                <tr>
                    <td>Costo produzione</td>
                    <td id="productionCostPerLiter" class="numeric">-</td>
                    <td id="totalProductionCost" class="numeric">-</td>
                </tr>
                <tr class="highlight">
                    <td><strong>Profitto</strong></td>
                    <td id="profitPerLiter" class="numeric">-</td>
                    <td id="totalProfit" class="numeric">-</td>
                </tr>
            </table>
        </div>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.9.1/chart.min.js"></script>

    <script>
        // Variabile per il grafico a torta
        let costPieChart = null;
        
        // Funzione principale di calcolo
        function calculateResults() {
            // Mostra la sezione dei risultati
            document.getElementById('resultsSection').style.display = 'block';
            
            // Recupero input principali
            const distillateType = document.getElementById('distillateType').value;
            const processCapacity = parseFloat(document.getElementById('processCapacity').value);
            const distillAmount = parseFloat(document.getElementById('distillAmount').value);
            const steamFlow = parseFloat(document.getElementById('steamFlow').value);
            const oilConcentration = parseFloat(document.getElementById('oilConcentration').value);
            const operatorMachines = parseFloat(document.getElementById('operatorMachines').value);
            
            // Recupero costi unitari
            const gasPrice = parseFloat(document.getElementById('gasPrice').value);
            const electricityPrice = parseFloat(document.getElementById('electricityPrice').value);
            const laborPrice = parseFloat(document.getElementById('laborPrice').value);
            const waterPrice = parseFloat(document.getElementById('waterPrice').value);
            
            // Recupero parametri nascosti
            const vacuumPumpPower = parseFloat(document.getElementById('vacuumPumpPower').value);
            const recyclingPumpsPower = parseFloat(document.getElementById('recyclingPumpsPower').value);
            const smallPumpsPower = parseFloat(document.getElementById('smallPumpsPower').value);
            const wellPumpPower = parseFloat(document.getElementById('wellPumpPower').value);
            const centrifugePower = parseFloat(document.getElementById('centrifugePower').value);
            const tanksPower = parseFloat(document.getElementById('tanksPower').value);
            const waterConsumption = parseFloat(document.getElementById('waterConsumption').value);
            const boilerEfficiency = parseFloat(document.getElementById('boilerEfficiency').value);
            const steamPerCubicMeterGas = parseFloat(document.getElementById('steamPerCubicMeterGas').value);
            
            // Calcoli intermedi
            const cycleDuration = (distillAmount / processCapacity) + 1.5;
            const operatorHours = cycleDuration;
            const totalVolume = distillAmount;
            const recoveredOil = totalVolume / 1000 * oilConcentration;
            const gasConsumption = (steamFlow * cycleDuration) / steamPerCubicMeterGas;
            
            // Consumi elettrici
            const vacuumPumpConsumption = vacuumPumpPower * cycleDuration;
            const pumpConsumption = (recyclingPumpsPower + smallPumpsPower + wellPumpPower) * cycleDuration;
            const utilitiesConsumption = (centrifugePower + tanksPower) * cycleDuration;
            const totalElectricityConsumption = vacuumPumpConsumption + pumpConsumption + utilitiesConsumption;
            
            // Calcolo costi
            const gasCost = Math.round(gasConsumption * gasPrice * 100) / 100;
            const electricityCost = totalElectricityConsumption * electricityPrice;
            const laborCost = laborPrice * operatorHours / operatorMachines;
            const waterCost = waterConsumption * waterPrice;
            
            // Costo totale
            const totalCost = gasCost + electricityCost + laborCost + waterCost;
            const costPerLiter = totalCost / recoveredOil;
            
            // Percentuali costi
            const gasPercentage = (gasCost / totalCost) * 100;
            const electricityPercentage = (electricityCost / totalCost) * 100;
            const laborPercentage = (laborCost / totalCost) * 100;
            const waterPercentage = (waterCost / totalCost) * 100;
            
            // Calcolo prezzo di vendita e profitto in base al tipo di distillato
            let sellingPricePerLiter = 0;
            if (distillateType === "MANDARINO") {
                sellingPricePerLiter = 30;
            } else if (distillateType === "LIMONE") {
                sellingPricePerLiter = 20;
            } else if (distillateType === "ARANCIA") {
                sellingPricePerLiter = 15;
            }
            
            const totalSellingPrice = sellingPricePerLiter * recoveredOil;
            const profitPerLiter = sellingPricePerLiter - costPerLiter;
            const totalProfit = totalSellingPrice - totalCost;
            
            // Aggiornamento output summary
            document.getElementById('cycleDuration').textContent = cycleDuration.toFixed(2) + " ore";
            document.getElementById('recoveredOil').textContent = recoveredOil.toFixed(2) + " litri";
            document.getElementById('totalCostSummary').textContent = totalCost.toFixed(2) + " €";
            document.getElementById('costPerLiterSummary').textContent = costPerLiter.toFixed(2) + " €/Lt";
            
            // Aggiornamento tabella costi
            document.getElementById('gasCost').textContent = gasCost.toFixed(2);
            document.getElementById('electricityCost').textContent = electricityCost.toFixed(2);
            document.getElementById('laborCost').textContent = laborCost.toFixed(2);
            document.getElementById('waterCost').textContent = waterCost.toFixed(2);
            document.getElementById('totalCost').textContent = totalCost.toFixed(2);
            
            document.getElementById('gasPercentage').textContent = gasPercentage.toFixed(2) + "%";
            document.getElementById('electricityPercentage').textContent = electricityPercentage.toFixed(2) + "%";
            document.getElementById('laborPercentage').textContent = laborPercentage.toFixed(2) + "%";
            document.getElementById('waterPercentage').textContent = waterPercentage.toFixed(2) + "%";
            
            // Aggiornamento tabella profitti
            document.getElementById('sellingPricePerLiter').textContent = sellingPricePerLiter.toFixed(2);
            document.getElementById('totalSellingPrice').textContent = totalSellingPrice.toFixed(2);
            document.getElementById('productionCostPerLiter').textContent = costPerLiter.toFixed(2);
            document.getElementById('totalProductionCost').textContent = totalCost.toFixed(2);
            document.getElementById('profitPerLiter').textContent = profitPerLiter.toFixed(2);
            document.getElementById('totalProfit').textContent = totalProfit.toFixed(2);
            
            // Colorazione del profitto (verde se positivo, rosso se negativo)
            const profitElements = [document.getElementById('profitPerLiter'), document.getElementById('totalProfit')];
            profitElements.forEach(el => {
                if (profitPerLiter > 0) {
                    el.classList.add('profit-positive');
                    el.classList.remove('profit-negative');
                } else {
                    el.classList.add('profit-negative');
                    el.classList.remove('profit-positive');
                }
            });
            
            // Aggiornamento grafico a torta
            updateCostPieChart(gasCost, electricityCost, laborCost, waterCost);
        }
        
        // Funzione per aggiornare il grafico a torta
        function updateCostPieChart(gasCost, electricityCost, laborCost, waterCost) {
            const ctx = document.getElementById('costPieChart').getContext('2d');
            
            // Distruggi il grafico precedente se esiste
            if (costPieChart) {
                costPieChart.destroy();
            }
            
            costPieChart = new Chart(ctx, {
                type: 'pie',
                data: {
                    labels: ['Gas naturale', 'Elettricità', 'Personale', 'Acqua'],
                    datasets: [{
                        data: [gasCost, electricityCost, laborCost, waterCost],
                        backgroundColor: [
                            'rgba(255, 99, 132, 0.7)',
                            'rgba(54, 162, 235, 0.7)',
                            'rgba(255, 206, 86, 0.7)',
                            'rgba(75, 192, 192, 0.7)'
                        ],
                        borderColor: [
                            'rgba(255, 99, 132, 1)',
                            'rgba(54, 162, 235, 1)',
                            'rgba(255, 206, 86, 1)',
                            'rgba(75, 192, 192, 1)'
                        ],
                        borderWidth: 1
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: {
                            position: 'right',
                            labels: {
                                font: {
                                    size: 14
                                }
                            }
                        },
                        title: {
                            display: true,
                            text: 'Ripartizione dei costi',
                            font: {
                                size: 16,
                                weight: 'bold'
                            }
                        },
                        tooltip: {
                            callbacks: {
                                label: function(context) {
                                    const label = context.label || '';
                                    const value = context.raw || 0;
                                    const total = context.dataset.data.reduce((a, b) => a + b, 0);
                                    const percentage = Math.round((value / total) * 100);
                                    return `${label}: ${value.toFixed(2)} € (${percentage}%)`;
                                }
                            }
                        }
                    }
                }
            });
        }
        
        // Esegui calcolo iniziale
        document.addEventListener('DOMContentLoaded', calculateResults);
    </script>
</body>
</html>
