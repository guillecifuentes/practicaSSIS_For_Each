# practicaSSIS_For_Each
Practica con SSIS y el control For Each que se encarga de leer archivos planos con la misma estructura desde un repositorio y se carga la data a una tabla

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
