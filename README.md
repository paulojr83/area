# Área

### Começando a entender o Golang
 
<pre>//Circ é responsável por calcular a área da cirucunferência </br>
func Circ(raio float64) float64
</pre><br>


<pre>// Rect é responsável por calcular a área de um retangulo </br>
func Rect(base, altura float64) float64
</pre>

 
<h3>Teste unitário básico

`
go test -cover .\matematica\
 
go test --coverprofile=resultado.out .\matematica\

go tool cover -func=resultado.out
 
go tool cover -html=resultado.out

`
 