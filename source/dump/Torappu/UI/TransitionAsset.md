# TransitionAsset

**Namespace:** `Torappu.UI`


## Fields

- `String _name`

- `String _fromState`

- `String _toState`

- `TransitionType _transitionType`

- `Boolean _isValid`

- `String _errorMessage`


## Properties

- `String name`

- `String FromState`

- `String ToState`

- `TransitionType TransType`

- `Boolean IsValid`

- `String ErrorMessage`


## Methods

- `String get_name()`

- `String get_FromState()`

- `Void set_FromState(String)`

- `String get_ToState()`

- `Void set_ToState(String)`

- `TransitionType get_TransType()`

- `Boolean get_IsValid()`

- `Void set_IsValid(Boolean)`

- `String get_ErrorMessage()`

- `Void set_ErrorMessage(String)`

- `String GenerateDescription()`

- `Boolean LogicEqual(TransitionAsset)`

- `Void _RefreshNameByOwnProperties()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class TransitionAsset
{
	public const String ANY_STATE; // 0x0
	private String _name; // 0x10
	private String _fromState; // 0x18
	private String _toState; // 0x20
	private TransitionType _transitionType; // 0x28
	private List`1 _staticActionSlot; // 0x30
	private Boolean _isValid; // 0x38
	private String _errorMessage; // 0x40

	public String name { get; }
	public String FromState { get; set; }
	public String ToState { get; set; }
	public TransitionType TransType { get; }
	public Boolean IsValid { get; set; }
	public String ErrorMessage { get; set; }

	// RVA: 0x2168e3c VA: 0x7594780e3c
	public String get_name() { }
	// RVA: 0x2168e44 VA: 0x7594780e44
	public String get_FromState() { }
	// RVA: 0x2168e4c VA: 0x7594780e4c
	public Void set_FromState(String value) { }
	// RVA: 0x21690c8 VA: 0x75947810c8
	public String get_ToState() { }
	// RVA: 0x21690d0 VA: 0x75947810d0
	public Void set_ToState(String value) { }
	// RVA: 0x21690ec VA: 0x75947810ec
	public TransitionType get_TransType() { }
	// RVA: 0x21690f4 VA: 0x75947810f4
	public Boolean get_IsValid() { }
	// RVA: 0x21690fc VA: 0x75947810fc
	public Void set_IsValid(Boolean value) { }
	// RVA: 0x2169108 VA: 0x7594781108
	public String get_ErrorMessage() { }
	// RVA: 0x2169110 VA: 0x7594781110
	public Void set_ErrorMessage(String value) { }
	// RVA: 0x2169118 VA: 0x7594781118
	private Void .ctor() { }
	// RVA: 0x21691c4 VA: 0x75947811c4
	public static TransitionAsset NewInstance() { }
	// RVA: 0x2169224 VA: 0x7594781224
	public String GenerateDescription() { }
	// RVA: 0x216946c VA: 0x759478146c
	public Boolean LogicEqual(TransitionAsset transAsset) { }
	// RVA: 0x21694d0 VA: 0x75947814d0
	public List`1 GetStaticActionSlot() { }
	// RVA: 0x2168e68 VA: 0x7594780e68
	private Void _RefreshNameByOwnProperties() { }
	// RVA: 0x2169468 VA: 0x7594781468
	private static String _GetStateName(String state) { }
}
```