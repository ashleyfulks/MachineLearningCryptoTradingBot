# MachineLearningCryptoTradingBot
Connects to CryptoML auto trade engine and sends signals to HaaSbot

Hi there. This code connects to 2 resources. One is a trade indicator system that will send this code a command (Command, Amount, Type and Limits)

Commands are: buy / sell
Amounts are represented in crypto decimal point to the 8th decimal ( eg 0.00000001 )
Type is the trade pair ( eg BTC/LTC )
Limits is the order type ( eg limit order, fill or kill, market, stop )

The second resource is an email system that receives the command and issues it via email. Haasbot is listening for the emails to show up and act on them. You could also send to an exchange directly via API.

