# practicaSSIS_For_Each
Practica con SSIS y el control For Each que se encarga de leer archivos planos con la misma estructura desde un repositorio y se carga la data a una tabla

Se basa en el siguiente video: https://youtu.be/K-o9k3TYaeM

--escript de creacion de la tabla que se alimentará
USE [Clientes]
GO

/****** Object:  Table [dbo].[VENTAS]    Script Date: 06/04/2022 03:19:24 p. m. ******/
SET ANSI_NULLS ON
GO

SET QUOTED_IDENTIFIER ON
GO

CREATE TABLE [dbo].[VENTAS](
	[IDCLIENTRE] [varchar](15) NULL,
	[NOMBRECLIENTE] [varchar](50) NULL,
	[CIUDAD] [varchar](25) NULL,
	[MONTO] [int] NULL,
	[FECHA_EVENTO] [datetime] NULL
) ON [PRIMARY]
GO


<img width="534" alt="Screenshot_1" src="https://user-images.githubusercontent.com/17502722/162074348-59d6f8b0-632f-4ea3-b48d-5c173424ac69.png">

<img width="283" alt="Screenshot_5" src="https://user-images.githubusercontent.com/17502722/162074321-0e392d79-f881-4817-b6de-7109aba803b8.png">
