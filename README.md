# Mascara Moeda Entry XamarinForms

Exemplo de aplicativo feito em Xamarin Forms aplicando máscara de moeda brasileira (R$) no Entry.

## Como utilizar

Adicione a classe MascaraMoeda no projeto compartilhado do seu aplicativo.

Na sua página xaml primeiro adicione o namespace da classe MascaraMoeda na tag ContentPage.
```
<ContentPage xmlns="http://xamarin.com/schemas/2014/forms"
   xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
   xmlns:local="clr-namespace:MascaraMoedaEntryXamarinForms"
   x:Class="MascaraMoedaEntryXamarinForms.MainPage">
```

Após isto basta inserir uma tag Entry na sua página, assim:
```
<Entry x:Name="EntryMoeda" Placeholder="R$ 0.000,00" Keyboard="Numeric" >
    <Entry.Behaviors>
        <local:MascaraMoeda />
    </Entry.Behaviors>
</Entry>
```

### Artigo com explicação

* [Máscara de moeda no Entry — Xamarin Forms](https://medium.com/code-expert/m%C3%A1scara-de-moeda-no-entry-xamarin-forms-4079cc603b30)
