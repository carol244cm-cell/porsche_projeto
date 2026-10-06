# porsche_projeto
DIO - EXCEL 
Porsche Sales Intelligence :root{--black:#050505;--ink:#111;--muted:#6e6e6e;--line:#dedede;--soft:#f4f4f2;--red:#d5001c;--white:#fff;} *{box-sizing:border-box} body{margin:0;background:#fff;color:var(--ink);font-family:Arial,Helvetica,sans-serif} .wrap{max-width:1500px;margin:auto;padding:28px 34px 42px} .top{display:flex;justify-content:space-between;align-items:flex-start;border-bottom:1px solid #111;padding-bottom:18px;margin-bottom:24px} .marca{font-weight:800;letter-spacing:.28em;font-size:24px} .sobrancelha{font-size:11px;letter-spacing:.22em;color:#777;text-transform:uppercase;margin-top:7px} .título{font-size:36px;letter-spacing:-.04em;font-weight:500;margin:0} .subtítulo{color:#6a6a6a;font-size:13px;margin-top:6px} .filtros{display:grid;grid-template-columns:repeat(4,1fr) auto;gap:12px;background:#f3f3f1;padding:14px;border:1px solid #e2e2e2;margin-bottom:20px} label{font-size:10px;text-transform:uppercase;letter-spacing:.15em;color:#666;display:block;margin-bottom:7px} select,button{height:42px;width:100%;border:1px solid #bbb;background:white;padding:0 12px;font-size:13px;color:#111} button{background:#111;color:#fff;border-color:#111;cursor:pointer;margin-top:17px;font-weight:700;letter-spacing:.06em} button:hover{background:#d5001c;border-color:#d5001c} .kpis{display:grid;grid-template-columns:repeat(5,1fr);gap:12px;margin-bottom:18px} .kpi{border:1px solid var(--line);padding:18px 18px 16px;min-height:112px;position:relative} .kpi:before{content:"";position:absolute;left:0;top:0;width:3px;height:100%;background:#111} .kpi .label{font-size:10px;color:#777;text-transform:uppercase;letter-spacing:.12em} .kpi .val{font-size:27px;font-weight:600;letter-spacing:-.03em;margin-top:13px} .kpi .sub{font-size:11px;color:#777;margin-top:4px} .grid{display:grid;grid-template-columns:1.1fr .9fr;gap:16px;margin-bottom:16px} .card{border:1px solid var(--line);background:#fff;padding:18px} .cardhead{display:flex;justify-content:space-between;align-items:flex-end;margin-bottom:8px} .card h2{font-size:16px;font-weight:600;margin:0} .card p{font-size:11px;color:#777;margin:5px 0 0} .chart{height:340px} .insight{background:#050505;color:white;padding:24px;min-height:180px} .insight .tag{font-size:10px;letter-spacing:.18em;color:#bbb;text-transform:uppercase} .insight h2{font-size:24px;font-weight:500;letter-spacing:-.03em;margin:10px 0 14px} .insight p{font-size:13px;color:#ddd;line-height:1.6;margin:0;max-width:900px} .insight strong{color:#fff} .tablewrap{max-height:430px;overflow:auto} table{width:100%;border-collapse:collapse;font-size:12px} th{text-align:left;background:#f5f5f3;position:sticky;top:0;padding:10px;border-bottom:1px solid #ccc;text-transform:uppercase;font-size:9px;letter-spacing:.12em;color:#666} td{padding:10px;border-bottom:1px solid #eee} td:last-child,th:last-child{text-align:right} .footer{font-size:10px;color:#777;margin-top:18px;display:flex;justify-content:space-between;gap:20px} @media(max-width:1050px){.filters,.kpis{grid-template-columns:repeat(2,1fr)}.grid{grid-template-columns:1fr}} @media(max-width:650px){.wrap{padding:18px}.filters,.kpis{grid-template-columns:1fr}.title{font-size:28px}.top{display:block}.brand{margin-bottom:18px}}

PORSCHE

Inteligência de Vendas · Painel Executivo

Desempenho de vendas
100 registros · dados normalizados para análise

Modelo PorscheTodos os modelos

CidadeTodas as cidades

Método de pagamentoTodos os métodos

Ano do modeloTodos os anos

REDEFINIR FILTROS

Vendas

—

veículos no recorte

Faturamento

—

valor total

Bilhete médio

—

por

Modelo líder

—

—

Ano líder

—

—

Principais modelos vendidos por cidade
Ranking de cidades e modelo líder em cada mercado

Qual ano de modelo mais vendido?
Distribuição das vendas por ano modelo

Carros populares por cidade
Modelo com maior frequência de venda em cada cidade

Cidade

Modelo líder

Vendas

Participação

Visão

—
—

Fonte: case porsche.xlsx · normalização de variações de texto aplicadas no dashboard.Interface inspirada na experiência digital Porsche Brasil. Porsche Brasil

const DATA=[{"id": 6, "date": "2024-02-29", "model": "718 Cayman", "year": 2022, "price": 79500.0, "payment": "Cartão de crédito", "city": "Boston", "state": "MA"}, {"id": 7, "date": "2024-03-14", "model": "911 Turbo S", "year": 2024, "price": 235000.0, "payment": "Transferência bancária", "city": "Seattle", "state": "WASHINGTON"}, {"id": 8, "date": "2024-04-18", "model": "Cayenne Coupe", "year": 2023, "price": 112750.0, "payment": {"id": 9, "date": null, "model": "Macan S", "year": 2021, "price": 68900.0, "payment": "À vista", "city": "Denver", "state": "COLORADO"}, {"id": 10, "date": "2024-05-22", "model": "Taycan 4S", "year": 2024, "price": 121000.0, "payment": "Transferência bancária", "city": "Los Angeles", "state": "CA"}, {"id": 11, "date": "2024-08-06", "model": "Panamera 4", "year": 2023, "price": {"id": 104500.0, "payment": "Cartão de crédito", "city": "Miami", "state": "FL"}, {"id": 12, "date": "2024-07-11", "model": "911 Carrera S", "year": 2020, "price": 96300.0, "payment": "Leasing", "city": "New York", "state": "NEW YORK"}, {"id": 13, "date": "2024-07-15", "model": "Cayenne E-Hybrid", "year": 2022, "price": 89750.0, "payment": "Transferência bancária", "city": "San Diego", "state": "CA"}, {"id": 14, "date": "2024-08-19", {"id": 15, "date": "2024-09-02", "model": "Macan GTS", "year": 2024, "price": 95000.0, "payment": "Financiamento", "city": "Phoenix", "state": "ARIZONA"}, {"id": 16, "date": "2024-09-17", "model": "Taycan Turbo", "year": 2023,"preço": 153200,5, "pagamento": "Transferência bancária", "cidade": "Dallas", "estado": "TX"}, {"id": 17, "data": "2024-10-31", "modelo": "911 GT3", "ano": 2024, "preço": 241000,0, "pagamento": "Transferência bancária", "cidade": "Las Vegas", "estado": "NV"}, {"id": 18, "data": "2024-05-11", "modelo": "Panamera Turbo S", "ano": 2022, "preço": 132.000,0, "pagamento": "À vista", "cidade": "San Jose", "estado": "CALIFORNIA"}, {"id": 19, "data": "2024-12-12", "modelo": "Cayenne Turbo GT", "ano": 2024, "preço": 188000,0, "pagamento": "Crypto", "cidade": "Houston", "estado": "TEXAS"}, {"id": 20, "data": "2024-12-25", "modelo": "911 Carrera Cabriolet", "ano": 2023, "preço": 127800,0, "pagamento": "Cartão de crédito", "cidade": "Atlanta", "estado": "GA"}, {"id": 21, "data": "2025-01-06", "modelo": "Macan", "ano": 2021, "preço": 58900,0, "pagamento": "Transferência bancário", "cidade": "Orlando", {"id": 22, "date": null, "model": "718 Spyder RS", "year": 2024, "price": 164000.0, "payment": "Financiamento", "city": "Portland", "state": "OR"}, {"id": 23, "date": "2025-02-14", "model": "Taycan Cross Turismo", "year": 2023, "price": 118500.0, "payment": "Transferência bancária", "city": "Charlotte", "state": "NC"}, {"id": 24, "date": null, "model": "Cayenne S", "year": 2022, "price": 91300.0, "payment": "Cartão de crédito", "city": "Nashville", {"id": 25, "date": "2025-03-21", "model": "911 Targa 4S", "year": 2024, "price": 158750.0, "payment": "Leasing", "city": "Minneapolis", "state": "MINNESOTA"}, {"id": 26, "date": "2025-03-28", "model": "Panamera", "year": 2020, "price": 72000.0, "payment": "Transferência Bancária", "city": "Philadelphia",{"id": 27, "date": "2025-04-09", "model": "Macan Electric", "year": 2025, "price": 86500.0, "payment": "Transferência bancária", "city": "San Antonio", "state": "TX"}, {"id": 28, "date": "2025-04-30", "model": "911 Dakar", "year": 2024, "price": 270000.0, "payment": "À vista", "city": "Salt Lake City", "state": "UTAH"}, {"id": 29, "date": "2025-05-12", "model": "Taycan GTS", "year": 2023, "price": 139000.0, "payment": "Financiamento", "city": "Raleigh", "state": "NC"}, {"id": 30, "date": "2025-06-18", "model": "Cayenne", "year": 2021, "price": 76800.0, "payment": "Cartão de crédito", "city": "Detroit", "state": "MICHIGAN"}, {"id": 31, "data": null, "modelo": "718 Cayman GT4 RS", "ano": 2024, "preço": 173600.0, "pagamento": "Transferência bancária", "cidade": "Columbus", "estado": "OH"}, {"id": 32, "data": "2025-07-07", "modelo": "911 Carrera GTS", "ano": 2022, {"id": 33, "date": "2025-07-22", "model": "Panamera 4 E-Hybrid", "year": 2023, "price": 109250.0, "payment": "Leasing", "city": "Fort Worth", "state": "TX"}, {"id": 34, "date": "2025-08-14", "model": "Macan T", "year": 2022, "price": 82000, "payment": "Transferência bancária", "city": "Jacksonville", "state": "FL"}, {"id": 35, "date": {"id": 2025-09-01", "model": "Taycan Turbo S", "year": 2025, "price": 214000.0, "payment": "Crypto", "city": "San Diego", "state": "CALIFORNIA"}, {"id": 36, "date": null, "model": "911 Carrera", "year": 2024, "price": 124500.0, "payment": "Cartão de crédito", "city": "Tampa", "state": "FL"}, {"id": 37, "date": "2025-09-18", "model": "Cayenne S",{"id": 2023, "price": 98200.0, "payment": "Transferência bancária", "city": "Sacramento", "state": "CALIFORNIA"}, {"id": 38, "date": "2025-10-04", "model": "Macan", "year": 2022, "price": 67500.0, "payment": "Financiamento", "city": "Cleveland", "state": "OH"}, {"id": 39, "date": "2025-10-12", "model": "Taycan", "year": 2025, "price": 116900.0, "payment": "Transferência bancária", "city": "Milwaukee", "state": "WISCONSIN"}, {"id": 40, "date": "2025-10-29", "modelo": "Panamera 4S", "ano": 2024, "preço": 112000,0, "pagamento": "À vista", "cidade": "Kansas City", "estado": "MO"}, {"id": 41, "data": "2025-02-11", "modelo": "718 Boxster", "ano": 2021, "preço": 74000,0, "pagamento": "Cartão de débito", "cidade": "Omaha", "estado": "NE"}, {"id": 42, "data": "2025-11-16", "modelo": "911 Turbo", "ano": 2024, "preço": 198300,0, "pagamento": "Transferência bancária", "cidade": "Albuquerque", {"id": 43, "date": null, "model": "Cayenne Coupe", "year": 2023, "price": 103750.0, "payment": "Transferência bancária", "city": "Tucson", "state": "AZ"}, {"id": 44, "date": null, "model": "Macan GTS", "year": 2024, "price": 93600.0, "payment": "Financiamento", "city": "Fresno", "state": "CA"}, {"id": 45, "date": "2025-12-07", "model": "Taycan 4S", "year": 2025, "price": 129000.0, "payment": "Transferência bancária", "city": "Virginia Beach", "estado": "VA"}, {"id": 46, "data": "2025-12-22", "modelo": "Panamera Turbo", "ano": 2022, "preço": 136000,0, "pagamento": "Cartão de crédito", "cidade": "Colorado Springs", "estado": "COLORADO"}, {"id": 47, "data": null, "modelo": "911 GT3 RS", "ano": 2024, "preço": 286500,0, "pagamento": "Transferência bancária", "cidade":{"id": 48, "date": "2026-01-08", "model": "Cayenne E-Hybrid", "year": 2023, "price": 92800.0, "payment": "Leasing", "city": "Bakersfield", "state": "CA"}, {"id": 49, "date": "2026-01-15", "model": "Macan T", "year": 2022, "price": 72400.0, "payment": "À vista", "city": "Mesa", "state": "ARIZONA"}, {"id": 50, "date": "2026-01-28", "model": "Taycan Turbo", "year": 2025, "price": 158500.0, "pagamento": "Criptomoeda", "cidade": "Atlanta", "estado": "GA"}, {"id": 51, "data": "2026-02-03", "modelo": "718 Cayman", "ano": 2021, "preço": 69900.0, "pagamento": "Transferência bancária", "cidade": "Long Beach", "estado": "CA"}, {"id": 52, "data": null, "modelo": "911 Targa 4", "ano": 2024, "preço": 141250.0, "pagamento": "Financiamento", "cidade": "Oakland", "estado": "Califórnia"}, {"id": 53, "data": "2026-02-19", "modelo": "Panamera", {"id": 54, "date": "2026-02-25", "model": "Cayenne Turbo", "year": 2023, "price": 146800.0, "payment": "Cartão de crédito", "city": "Wichita", "state": "KANSAS"}, {"id": 55, "date": "2026-03-01", "model": "Macan Electric", "year": 2025, "price": 89700.0, "payment": "Leasing", "city": "New Orleans", "state": "LA"}, {"id": 56, "date": "2026-03-14", "modelo": "911 Carrera S", "ano": 2022, "preço": 104600,0, "pagamento": "Transferência bancária", "cidade": "Honolulu", "estado": "HI"}, {"id": 57, "data": nulo, "modelo": "Taycan GTS", "ano": 2024, "preço": 142000,0, "pagamento": "Transferência bancária", "cidade": "Anaheim", "estado": "CA"}, {"id": 58, "data": "2026-04-08", "modelo": "Cayenne",{"id": 2021, "price": 78400.0, "payment": "À vista", "city": "Henderson", "state": "NEVADA"}, {"id": 59, "date": null, "model": "718 Spyder RS", "year": 2025, "price": 169000.0, "payment": "Financiamento", "city": "Lexington", "state": "KY"}, {"id": 60, "date": "2026-04-21", "model": "911 Dakar", "year": 2024, "price": 268900.0, "payment": "Cartão de crédito", "city": "Riverside", "state": "CALIFORNIA"}, {"id": 61, "date": {"id": 2026-04-29", "model": "Panamera 4", "year": 2023, "price": 101300.0, "payment": "Transferência bancária", "city": "Corpus Christi", "state": "TX"}, {"id": 62, "date": "2026-05-05", "model": "Macan S", "year": 2021, "price": 66750.0, "payment": "À vista", "city": "St. Louis", "state": "MISSOURI"}, {"id": 63, "date": "2026-05-14", "model": "Taycan Cross Turismo", "year": 2024, "price": 127900.0, "payment": "Leasing", "city": "Pittsburgh", {"id": 64, "date": "2026-05-23", "model": "Cayenne Turbo GT", "year": 2025, "price": null, "payment": "Transferência bancária", "city": "Cincinnati", "state": "OH"}, {"id": 65, "date": "2026-06-02", "model": "911 Carrera Cabriolet", "year": 2023, "price": 132000.0, "payment": "Crypto", "city": "Anchorage", "state": "ALASKA"}, {"id": 66, "date": "2026-06-15", "model": "718 Cayman GT4 RS", "year": 2024, "price": 176400.0, "pagamento": "Cartão de crédito", "cidade": "Plano", "estado": "TX"}, {"id": 67, "data": null, "modelo": "Panamera 4 E-Hybrid", "ano": 2022, "preço": 108500.0, "pagamento": "Transferência bancária", "cidade": "Newark", "estado": "NJ"}, {"id": 68, "data": "2026-07-07", "modelo": "Macan", "ano": 2021, "preço": 59000,0, "pagamento": "Financiamento", "cidade":{"id": 69, "date": "2026-07-20", "model": "Taycan Turbo S", "year": 2025, "price": 218000.0, "payment": "Transferência bancária", "city": "Lincoln", "state": "NEBRASKA"}, {"id": 70, "date": null, "model": "Cayenne S", "year": 2024, "price": 99950.0, "payment": "Cartão de débito", "city": "Jersey City", "state": "NJ"}, {"id": 71, "date": "2026-04-08", "model": "911 Carrera GTS", "year": 2024, "price": {"id": 121750.0, "payment": "Cartão de crédito", "city": "Chandler", "state": "AZ"}, {"id": 72, "date": "2026-08-18", "model": "718 Boxster GTS", "year": 2023, "price": 91500.0, "payment": "Leasing", "city": "Reno", "state": "NV"}, {"id": 73, "date": "2026-08-31", "model": "Panamera Turbo S", "year": 2022, "price": 134000.0, "payment": "Transferência bancária", "city": "Buffalo", "state": "NEW YORK"}, {"id": 74, "date": "2026-09-09", "modelo": "Macan GTS", "ano": 2024, "preço": 96800,0, "pagamento": "Transferência bancária", "cidade": "Durham", "estado": "NC"}, {"id": 75, "data": "17/09/2026", "modelo": "Taycan 4S", "ano": 2025, "preço": 131600.0, "pagamento": "Transferência bancária", "cidade": "Laredo", "estado": "TEXAS"}, {"id": 76, "data": "2026-09-28", "modelo": "Cayenne E-Hybrid", "ano": 2023, "preço": 94300.0, "pagamento": "À vista", "cidade": "Madison", "estado": "WISCONSIN"}, {"id": 77, "date": "2026-10-06", "model": "911 Turbo S", "year": 2025, "price": 242000.0, "payment": "Crypto", "city": "Lubbock", "state": "TX"}, {"id": 78, "date": "2026-10-16", "model": "718 Cayman S", "year": 2022, "price": 82750.0, "payment": "Cartão de crédito", "city": "Toledo", "state": "OHIO"}, {"id": 79, "date":{"id": 2026-10-29", "model": "Macan Electric", "year": 2026, "price": 91300.0, "payment": "Transferência bancária", "city": "Irvine", "state": "CA"}, {"id": 80, "date": "2026-11-03", "model": "Panamera", "year": 2021, "price": 79900.0, "payment": "Financiamento", "city": "Garland", "state": "TX"}, {"id": 81, "date": null, "model": "Cayenne Coupe", "year": 2024, "price": 111000.0, "payment": "Transferência bancária", "city": "Irving", "state": "TX"}, {"id": 82, {"id": 83, "date": "2026-12-24", "model": "Taycan", "year": 2025, "price": 119900.0, "payment": "Leasing", "city": "Scottsdale", "state": "ARIZONA"}, {"id": 84, "date": null, "model": "Macan T", "year": 2022, "price": 73200.0, "payment": "Transferência bancária", "city": "Norfolk", "state": "VA"}, {"id": 85, "data": "2026-12-28", "modelo": "911 GT3", "ano": 2024, "preço": 224000.0, "pagamento": "Transferência bancária", "cidade": "Boise", "estado": "IDAHO"}, {"id": 86, "data": "2027-01-15", "modelo": "911 Carrera", "ano": 2024, "preço": 126900.0, "pagamento": "Cartão de crédito", "cidade": "Orlando", "estado": "FL"}, {"id": 87, "data": "2027-01-29", "modelo": "Cayenne", "ano": 2023, "preço": 84.500,0, "pagamento": "Transferência bancária", "cidade": "San Jose", "estado": "CALIFORNIA"}, {"id": 88, "data": "2027-02-11", "modelo": "Macan S", "ano": 2022, "preço": 69800,0, "pagamento": "Financiamento", "cidade": "Tampa", "estado": "FL"}, {"id": 89, "data": null, "modelo": "Taycan 4S", "ano": 2025, "preço": 132700,0, "pagamento": "Transferência bancária",{"id": "Denver", "state": "COLORADO"}, {"id": 90, "date": "2027-03-05", "model": "Panamera", "year": 2021, "price": 81000.0, "payment": "À vista", "city": "Austin", "state": "TX"}, {"id": 91, "date": "2027-03-18", "model": "718 Cayman", "year": 2023, "price": 78900.0, "payment": "Cartão de débito", "city": "Seattle", "state": "WA"}, {"id": 92, "date": "2027-04-02", "model": "911 Turbo S", "year": 2026, "price": 249300.0, "pagamento": "Transferência bancária", "cidade": "Boston", "estado": "MASSACHUSETTS"}, {"id": 93, "data": null, "modelo": "Cayenne Coupe", "ano": 2024, "preço": 108750.0, "pagamento": "Transferência bancária", "cidade": "Phoenix", "estado": "AZ"}, {"id": 94, "data": null, "modelo": "Macan Electric", "ano": 2026, "preço": 92600.0, "pagamento": "Financiamento", "cidade": "Chicago", "estado": "ILLINOIS"}, {"id": 95, "data": "2027-05-12", "modelo": "Taycan Turbo", "ano": 2025, "preço": 164000,0, "pagamento": "Transferência bancária", "cidade": "Dallas", "estado": "TX"}, {"id": 96, "data": "2027-05-27", "modelo": "Panamera 4S", "ano": 2024, "preço": 119000,0, "pagamento": "Cartão de crédito", "cidade": "São Francisco", "estado": "CALIFORNIA"}, {"id": 97, "data": null, "modelo": "911 GT3", "ano": 2026, "preço": 232500.0, "pagamento": "Transferência bancária", "cidade": "Las Vegas", "estado": "NV"}, {"id": 98, "data": "2027-06-18", "modelo": {"id": 99, "date": "2027-07-03", "model": "Macan T", "year": 2022, "price": 74400.0, "payment": "À vista", "city": "Mesa", "state": "ARIZONA"}, {"id": 100, "date": "2027-07-22", "model":{"id": 101, "date": "2027-08-08", "model": "718 Boxster", "year": 2021, "price": 71900.0, "payment": "Transferência Bancária", "city": "Long Beach", "state": "CA"}, {"id": 102, "date": null, "model": "911 Targa 4", "year": 2024, "price": 143250.0, "payment": "Financiamento", "city": "Oakland", "state": "CALIFORNIA"}, {"id": 103, {"id": 104, "date": "2027-09-25", "model": "Cayenne Turbo GT", "year": 2025, "price": 204800.0, "payment": "Cartão de crédito", "city": "Wichita", "state": "KANSAS"}, {"id": 105, "date": "2027-10-01", "model": "911 Dakar", "year": 2024, "price": 271700.0, "payment": "Leasing", "city": "New"} Orleans", "estado": "LA"}]; const{"id": 105, "date": "2027-10-01", "model": "911 Dakar", "year": 2024, "price": 271700.0, "payment": "Leasing", "city": "New Orleans", "state": "LA"}]; const{"id": 105, "date": "2027-10-01", "model": "911 Dakar", "year": 2024, "price": 271700.0, "payment": "Leasing", "city": "New Orleans", "state": "LA"}]; const
Não foi possível renderizar a expressão.
$=id=>document.getElementById(id); const uniq=(a,k)=>[...new Set(a.map(x=>x[k]).filter(v=>v!==null&&v!==undefined&&v!==''))].sort((a,b)=>String(a).localeCompare(String(b),'pt-BR')); function fill(id,vals){const s=$(id); vals.forEach(v=>{const o=document.createElement('option');o.value=v;o.textContent=v;s.appendChild(o)})} fill('model',uniq(DATA,'model')); fill('city',uniq(DATA,'city')); fill('payment',uniq(DATA,'payment')); fill('year',uniq(DATA,'year')); function filtered(){let a=DATA; for(const [id,key] of [['model','model'],['city','city'],['payment','payment'],['year','year']]){const v=$(id).value;if(v!=='ALL')a=a.filter(x=>String(x[key])===String(v))}return a} const money=n=>n==null?'—':new Intl.NumberFormat('en-US',{style:'currency',currency:'USD',maximumFractionDigits:0}).format(n); const pct=n=>`${(n*100).toFixed(1)}%`; função counts(a,key){const m={};a.forEach(x=>{const v=x[key]??'N/D';m[v]=(m[v]||0)+1});return Object.entries(m).sort((a,b)=>b[1]-a[1])} função update(){const a=filtered(), n=a.length, revenue=a.reduce((s,x)=>s+(x.price||0),0), ticket=n?revenue/n:0;
(
′
k
S
um
l
e
s
′
)
.
t
e
x
t
C
o
n
t
e
n
t
=
n
.
t
o
L
o
c
um
l
e
S
t
r
eu
n
g
(
′
p
t
−
B
R
′
)
;
('kRevenue').textContent=money(receita);
(
′
k
T
eu
c
k
e
t
′
)
.
t
e
x
t
C
o
n
t
e
n
t
=
m
o
n
e
y
(
t
eu
c
k
e
t
)
;
c
o
n
s
t
m
c
=
c
o
u
n
t
s
(
um
,
′
m
o
d
e
l
′
)
,
y
c
=
c
o
u
n
t
s
(
um
,
′
y
e
um
r
′
)
;
c
o
n
s
t
l
m
=
m
c
[
0
]
,
l
y
=
y
c
[
0
]
;
('kModel').textContent=lm?lm[0]:'—';
(
′
k
M
o
d
e
l
S
u
b
′
)
.
t
e
x
t
C
o
n
t
e
n
t
=
l
m
?
'
{lm[1]} vendas ·
p
c
t
(
l
m
[
1
]
/
n
)
d
o
r
e
c
o
r
t
e
'
:
′
—
′
;
('kAno').textContent=ly?ly[0]:'—';
(
′
k
Y
e
um
r
S
u
b
′
)
.
t
e
x
t
C
o
n
t
e
n
t
=
l
y
?
'
{ly[1]} vendas · ${pct(ly[1]/n)} do recorte`:'—'; const cityCounts=counts(a,'city').slice(0,12); const labels=cityCounts.map(x=>x[0]).reverse(), vals=cityCounts.map(x=>x[1]).reverse(); const topModelsByCity=cityCounts.map(([city,count])=>{const cc=counts(a.filter(x=>x.city===city),'model');return cc[0]?[cc[0][0],cc[0][1]]:['—',0]}).reverse(); Plotly.react('cityChart',[{type:'bar',orientation:'h',y:labels,x:vals,text:topModelsByCity.map(x=>x[0]),customdata:topModelsByCity.map(x=>x[1]),hovertemplate:' %{y}
Vendas: %{x}
Modelo líder: %{text} (%{customdata})',marker:{color:'#111'}}],{margin:{l:90,r:20,t:10,b:35},paper_bgcolor:'transparent',plot_bgcolor:'transparent',xaxis:{gridcolor:'#eee',dtick:1},yaxis:{automargin:true},font:{family:'Arial',size:11,color:'#111'},showlegend:false},{displayModeBar:false,responsive:true}); const ylabels=yc.map(x=>String(x[0])).reverse(), yvals=yc.map(x=>x[1]).reverse(); Plotly.react('yearChart',[{type:'bar',orientation:'h',y:ylabels,x:yvals,text:yvals.map(String),textposition:'outside',marker:{color:'#777'},hovertemplate:'Ano: %{y}
Vendas: %{x}'}],{margin:{l:60,r:35,t:10,b:35},paper_bgcolor:'transparent',plot_bgcolor:'transparent',xaxis:{gridcolor:'#eee',dtick:1},yaxis:{dtick:1},font:{family:'Arial',size:11,color:'#111'},showlegend:false},{displayModeBar:false,responsive:true}); const allCities=counts(a,'city'); const rows=allCities.map(([city,count])=>{const cc=counts(a.filter(x=>x.city===city),'model');const leader=cc[0]||['—',0];return [city,leader[0],leader[1],leader[1]/count]});
(
′
c
eu
t
y
T
um
b
l
e
′
)
.
eu
n
n
e
r
H
T
M
L
=
r
o
c
s
.
m
um
p
(
r
=>
'
{r[0]}${r[1]}${r[2]}${pct(r[3])}`).join(''); let title='Leitura geral do mercado', text=''; if(!n){title='Sem dados no recorte';text='Ajuste os filtros para visualizar os principais padrões de venda.'} else if(
Braçadeira aberta extra ou braçadeira fechada ausente
$("cidade").value!=='TODOS'){const c=$("cidade").valor, cc=contagens(a,'modelo'); title=`${c} · ${cc[0]?.[0]||'sem modelo líder'}`; text=`No recorte selecionado, ${cc[0]?.[0]||'o modelo líder'} concentra ${cc[0]?.[1]||0} venda(s). Isso indica o carro mais popular dentro da cidade comprovada. O painel pode ser usado para comparar esse comportamento com outras cidades e anos.`} else {const topCity=allCities[0], cc=topCity?counts(a.filter(x=>x.city===topCity[0]),'model'):[]; title=topCity?`${topCity[0]} lidera em volume`:'Mercado'; text=topCity?`A cidade com maior número de vendas no recorte tem ${topCity[1]} venda(s), e seu modelo mais frequente é ${cc[0]?.[0]||'—'}. O ano ${ly?.[0]||'—'} é o ano-modelo mais vendido, enquanto ${lm?.[0]||'—'} aparece como o modelo líder geral.`:'Sem dados suficientes.'}
(
′
eu
n
s
eu
g
h
t
T
eu
t
l
e
′
)
.
t
e
x
t
C
o
n
t
e
n
t
=
t
eu
t
l
e
;
('insightText').textContent=texto; } ['model','city','payment','year'].forEach(id=>$(id).addEventListener('change',update));
Braçadeira aberta extra ou braçadeira fechada ausente
$('reset').addEventListener('click',()=>{['model','city','payment','year'].forEach(id=>$
