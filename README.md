# Fashion-name
Aplicação de gestão de stock e venda de roupas 

<?xml version="1.0" encoding="utf-8" ?>
<ContentPage
    xmlns="http://schemas.microsoft.com/dotnet/2021/maui"
    xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
    x:Class="FashionStock.MainPage"
    BackgroundColor="#F3F6FC">

    <ScrollView>
        <VerticalStackLayout Padding="25" Spacing="20">

            <Label
                Text="FASHION STOCK"
                FontSize="28"
                FontAttributes="Bold"
                TextColor="#1565C0"
                HorizontalOptions="Center"/>

            <Label
                Text="Gestão de Stock e Vendas"
                FontSize="16"
                TextColor="Gray"
                HorizontalOptions="Center"/>

            <Frame
                BackgroundColor="#1565C0"
                CornerRadius="15"
                Padding="20">

                <VerticalStackLayout>
                    <Label Text="Bem-vindo!"
                           TextColor="White"
                           FontSize="24"
                           FontAttributes="Bold"/>

                    <Label Text="Controla os teus produtos e vendas."
                           TextColor="White"
                           FontSize="14"/>
                </VerticalStackLayout>
            </Frame>

            <Button Text="📦 Produtos"
                    BackgroundColor="#1565C0"
                    TextColor="White"
                    CornerRadius="12"/>

            <Button Text="🛒 Vendas"
                    BackgroundColor="#1565C0"
                    TextColor="White"
                    CornerRadius="12"/>

            <Button Text="📊 Relatórios"
                    BackgroundColor="#1565C0"
                    TextColor="White"
                    CornerRadius="12"/>

            <Button Text="⚙️ Definições"
                    BackgroundColor="#1565C0"
                    TextColor="White"
                    CornerRadius="12"/>

        </VerticalStackLayout>
    </ScrollView>

</ContentPage>
