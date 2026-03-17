<%@ Page Language="C#" AutoEventWireup="true" CodeBehind="index.aspx.cs" Inherits="CalculadoraWebForms.index" %>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title></title>
</head>
<body>
    <h1>Minha Calculadora WebForms</h1>
    <form id="form1" runat="server">
        <asp:Label ID="Label1" runat="server" Text="Primeiro Numero"></asp:Label><br />
        <asp:TextBox ID="TextNro1" runat="server"></asp:TextBox><br />
        <asp:Label ID="Label2" runat="server" Text="Segundo Numero"></asp:Label><br />
           <asp:TextBox ID="TextNro2" runat="server"></asp:TextBox><br /><br />
        <asp:Button ID="btSomar" runat="server" Text="Somar" OnClick="btSomar_Click" />
         <asp:Button ID="btSubtrair" runat="server" Text="Subtrair" OnClick="btSubtrair_Click" />
         <asp:Button ID="btMultiplicar" runat="server" Text="Multiplicar" OnClick="btMultiplicar_Click"/>
         <asp:Button ID="btDividir" runat="server" Text="Dividir" OnClick="btDividir_Click" style="height: 29px"/>
        <br /><br />
        O resultado é: <asp:Label ID="lblResultado" runat="server" Text="0"></asp:Label>
    </form>
</body>
</html>
