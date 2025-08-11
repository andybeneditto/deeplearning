El análisis presentado en el TP de Deep Learning consta de lo siguiente:

Se busca entender si existe una correlación entre Consumos de Tarjeta de Crédito y Saldos Vista ($$ en Caja de Ahorro) de los clientes, esto es debido a que en el rubro bancario se encaran muchas estrategias comerciales para impulsar el consumo de TC,
donde la principal alerta es que las TC son un producto deficitario para los Bancos (el Banco al financiar a un cliente con su uso de la TC, en general pierde dinero).
Sin embargo, hay una creencia infundada en que un cliente que consume mucho con TC, deja más dinero en su caja de ahorro (para pagar la TC, por que transacciona más, etc etc).

Uno de los principales ingresos de los Bancos son el margen financiero que obtienen de los Saldos Vista ($$ en caja de ahorro), ya que es un fondeo prácticamente gratis de dinero, el cuál luego usan para en general dar prestamos,
donde cobran altas tasas de intereses (por dinero que obtuvieron en buena medida "gratis").

Con lo cuál, el impulso del consumo de TC de los clientes, viene dado por la premisa de que la pérdida que genera la TC, es sobrecompensada por el Margen Financiero que traen esos Saldos Vista incrementales que deja el cliente.
Es por esto, que entender si de verdad existe esta correlación entre estas variables, es importante.

Por otro lado, desde el punto de vista de LSTM, es relevante poder predecir los futuros Saldos Vista que tenga un cliente, para poder alinear estrategias de fondeo y de colocación de esos fondos, a futuro.
