# ActionBinding

**Namespace:** `AdvancedInspector`


## Fields

- `GameObject gameObject`

- `Component component`

- `String method`

- `ActionEventHandler OnInvoke`


## Properties

- `GameObject GameObject`

- `Component Component`

- `MethodInfo Method`


## Methods

- `GameObject get_GameObject()`

- `Void set_GameObject(GameObject)`

- `Component get_Component()`

- `Void set_Component(Component)`

- `IList GetComponents()`

- `MethodInfo get_Method()`

- `Void set_Method(MethodInfo)`

- `IList GetMethods()`

- `Boolean IsMethodValid(MethodInfo)`

- `String GetParamNames(String, ParameterInfo[])`

- `MethodInfo GetMethodInfo()`

- `Void add_OnInvoke(ActionEventHandler)`

- `Void remove_OnInvoke(ActionEventHandler)`

- `Void Invoke(Object[])`

- `Boolean Copiable(Object)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class ActionBinding : ICopiable
{
	private String[] internalParameters; // 0x10
	private GameObject gameObject; // 0x18
	private Component component; // 0x20
	private String method; // 0x28
	private BindingParameter[] parameters; // 0x30
	private ActionEventHandler OnInvoke; // 0x38

	public GameObject GameObject { get; set; }
	public Component Component { get; set; }
	public MethodInfo Method { get; set; }

	// RVA: 0x1b1c278 VA: 0x7594134278
	public GameObject get_GameObject() { }
	// RVA: 0x1b1c280 VA: 0x7594134280
	public Void set_GameObject(GameObject value) { }
	// RVA: 0x1b1c3c0 VA: 0x75941343c0
	public Component get_Component() { }
	// RVA: 0x1b1c320 VA: 0x7594134320
	public Void set_Component(Component value) { }
	// RVA: 0x1b1c630 VA: 0x7594134630
	private IList GetComponents() { }
	// RVA: 0x1b1c964 VA: 0x7594134964
	public MethodInfo get_Method() { }
	// RVA: 0x1b1c3c8 VA: 0x75941343c8
	public Void set_Method(MethodInfo value) { }
	// RVA: 0x1b1d12c VA: 0x759413512c
	private IList GetMethods() { }
	// RVA: 0x1b1d778 VA: 0x7594135778
	private Boolean IsMethodValid(MethodInfo info) { }
	// RVA: 0x1b1d904 VA: 0x7594135904
	private String GetParamNames(String name, ParameterInfo[] param) { }
	// RVA: 0x1b1c968 VA: 0x7594134968
	private MethodInfo GetMethodInfo() { }
	// RVA: 0x1b1de4c VA: 0x7594135e4c
	public Void add_OnInvoke(ActionEventHandler value) { }
	// RVA: 0x1b1dee8 VA: 0x7594135ee8
	public Void remove_OnInvoke(ActionEventHandler value) { }
	// RVA: 0x1b1df84 VA: 0x7594135f84
	public Void .ctor() { }
	// RVA: 0x1b1e020 VA: 0x7594136020
	public Void .ctor(Type[] types) { }
	// RVA: 0x1b1e18c VA: 0x759413618c
	public Void Invoke(Object[] args) { }
	// RVA: 0x1b1e660 VA: 0x7594136660
	public override String ToString() { }
	// RVA: 0x1b1e9f0 VA: 0x75941369f0
	public Boolean Copiable(Object destination) { }
}
```