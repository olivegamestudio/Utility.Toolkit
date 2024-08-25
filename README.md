# Utility.Toolkit

A utility library of various toolkit type classes.

## Installation

You can use the NUGET package named **Utility.Toolkit** that is on nuget.org or adding this line to an **ItemGroup** section in your csproj file.

```
<PackageReference Include="Utility.Toolkit" Version="*" />
```

## Usage Examples

### Taking the ObservableObject one step further with defining a model type.

```
public partial class MyViewModel : ObservableObject<MyModel>
{
  public MyClass(MyModel myModel) : base(myModel)
  {
  }
}
```

