# Foldout

**Namespace:** ` `


## Fields

- `Boolean _doNotIndentChildControl`


## Properties

- `Boolean IndentChildControl`


## Methods

- `Boolean get_IndentChildControl()`

- `Void set_IndentChildControl(Boolean)`

- `tkFoldoutMetadata GetMetadata(fiGraphMetadata)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Foldout : tkControl`2
{
	private readonly GUIStyle _foldoutStyle; // 0x0
	private readonly fiGUIContent _label; // 0x0
	private readonly tkControl`2 _control; // 0x0
	private readonly Boolean _defaultToExpanded; // 0x0
	private Boolean _doNotIndentChildControl; // 0x0
	public Nullable`1 HierarchyMode; // 0x0

	public Boolean IndentChildControl { get; set; }

	// RVA: 0x VA: 0x0
	public Boolean get_IndentChildControl() { }
	// RVA: 0x VA: 0x0
	public Void set_IndentChildControl(Boolean value) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(fiGUIContent label, tkControl`2 control) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(fiGUIContent label, FontStyle fontStyle, tkControl`2 control) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(fiGUIContent label, FontStyle fontStyle, Boolean defaultToExpanded, tkControl`2 control) { }
	// RVA: 0x VA: 0x0
	private tkFoldoutMetadata GetMetadata(fiGraphMetadata metadata) { }
	// RVA: 0x VA: 0x0
	protected override T DoEdit(Rect rect, T obj, TContext context, fiGraphMetadata metadata) { }
	// RVA: 0x VA: 0x0
	protected override Single DoGetHeight(T obj, TContext context, fiGraphMetadata metadata) { }
}
```