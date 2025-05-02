# PropertyEditor

**Namespace:** ` `


## Fields

- `MemberInfo _attributes`

- `Type _fieldType`

- `String _errorMessage`


## Methods

- `Void InitializeFromMemberName(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PropertyEditor : tkControl`2
{
	private MemberInfo _attributes; // 0x0
	private Func`3 _getValue; // 0x0
	private Action`3 _setValue; // 0x0
	private Value`1 _label; // 0x0
	private Type _fieldType; // 0x0
	private String _errorMessage; // 0x0


	// RVA: 0x VA: 0x0
	private Void InitializeFromMemberName(String memberName) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(String memberName) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(fiGUIContent label, String memberName) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Value`1 label, String memberName) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(fiGUIContent label, Type fieldType, MemberInfo attributes, Func`3 getValue, Action`3 setValue) { }
	// RVA: 0x VA: 0x0
	public static PropertyEditor Create(fiGUIContent label, MemberInfo attributes, Func`3 getValue, Action`3 setValue) { }
	// RVA: 0x VA: 0x0
	public static PropertyEditor Create(fiGUIContent label, Func`3 getValue) { }
	// RVA: 0x VA: 0x0
	public static PropertyEditor Create(fiGUIContent label, Func`3 getValue, Action`3 setValue) { }
	// RVA: 0x VA: 0x0
	protected override T DoEdit(Rect rect, T obj, TContext context, fiGraphMetadata metadata) { }
	// RVA: 0x VA: 0x0
	protected override Single DoGetHeight(T obj, TContext context, fiGraphMetadata metadata) { }
}
```