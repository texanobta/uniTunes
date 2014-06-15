uniTunes
========================

- Aplicação Web criada para a cadeira de Arquitetura de Software.

========================
	Entregas:
	- Data de Entrega Parcial: 12/06
	- Data de Entrega Final: 19/06
========================
	Architecture:
	ASP.NET MVC 5

	Front-end: HTML5, CSS3, Javascript
	Javascript libraries: jQuery
	Design Patterns and Practices: Code-First, Entity Framework, Unit of Work, Repositories, Dependency Injection (StructureMap)
	Others: Windows Azure (Host), Amazon RDS (SGBD: SQL Server), Twitter Bootstrap
========================
	Solution:
	- uniTunes.Common
		- Extensions, Helpers
	- uniTunes.Data
	  	- Data access Layer
		- Configuration, Initializers and Infrastructure.
		- Generic repository and individuals repositories.
	- uniTunes.Models
		- Models, Classes
	- uniTunes.Services
		- Business logic and rules
	- uniTunes.Tests
		- Unit tests
	- uniTunes.UI
		- Controllers, Views (Front-end)
