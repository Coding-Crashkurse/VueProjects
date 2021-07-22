# A/B Test

Dieses Repository enthält 2 VueJS Apps mit verschiedenen Designs. Ein Endnutzer kann über `localhost:8080` die Apps auf dem Browser erreichen. Dort übernimmt nginx die Verteilung der requests auf app1 und app2.

<br>

Das `split_clients` directive sorgt dafür, dass der Traffic den darin angegebenen Prozentzahlen verteilt wird. In diesem Fall wird 80% vom Traffic auf App A und der Rest auf App B verteilt.