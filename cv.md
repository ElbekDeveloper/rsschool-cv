# Elbek's Resume

### .Net Developer

Extremely motivated to
constantly develop my skills
and grow professionally. My
aim to contribute on the
community I am working in...

#### Basic Info

1. Full Name: Elbek Normurudov (ElbekDeveloper)
2. Please, click in the following links to get in touch with me:
   - [My Telegram](https://t.me/sochiquzmanager)
   - By calling to: 91 449 01 33
   - e.normudov@mail.ru

### Skills

- Exceptional communication and networking skills;
- Successful working in a team environment, as well as independently;
- The ability to work under pressure and multi-task;
- The ability to follow instructions and deliver quality results;

### Code Examples

The code below ensures that all types are registered for further use via dependency injection.
The project helped to practice **SOLID** principles

```csharp
builder.RegisterType<InputService>().As<IInputService>();
builder.RegisterType<SqlConnectionAs<ISqlConnection>();
builder.RegisterType<TokenServiceAs<ITokenService>();
builder.RegisterType<SumCalculatorAs<ISumCalculator>();
builderRegisterType<CounterAgentInserterAs<ICounterAgentInserter>();
builder.RegisterType<StandardMessages().As<IStandardMessages>();
builder.RegisterType<SearchFeatureAs<ISearchFeature>();
builder.RegisterType<DeleteRowFeature().As<IDeleteRow>();

```

One more peace of code to document _sql connection_

```csharp
public interface ISqlConnection
    {
        void Close();
        void Open();
        NpgsqlConnection GetConnection();
    }
```

```csharp
public class SqlConnection : ISqlConnection
  {
      private NpgsqlConnection connection;
      public SqlConnection()
      {
          connection = new NpgsqlConnectio(Database.GetConnectionString());
      }
      public void Close()
      {
          connection.Close();
      }
      public void Open()
      {
          connection.Open();
      }
      public NpgsqlConnection GetConnection()=> connection;
  }
```

### Experience

| Position                  |        Company         |        Period         |                           **What I have done** |
| :------------------------ | :--------------------: | :-------------------: | ---------------------------------------------: |
| Freelancer                |     Self-employed      |  MAY 2020 - AUG 2020  | Developed Pharmacy Inventory Management System |
| Software Developer Intern |      ZetSoft LLC       | FEB 2020 - MARCH 2020 |  Tested the project that was under development |
| IELTS instructor          | Active English Courses |  DEC 2016 - SEP 2018  |                        Delivered IELTS lessons |
