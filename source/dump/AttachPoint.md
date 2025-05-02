# AttachPoint

**Namespace:** ` `


## Fields

- `Transform _targetPoint`

- `String _animationKey`

- `LeftOrRight _leftOrRight`

- `Boolean _specifyDir`

- `Vector2 _interactTime`

- `String _interactId`


## Properties

- `Transform targetPoint`

- `String animationKey`

- `LeftOrRight leftOrRight`

- `Boolean specifyDir`

- `Vector2 interactTime`

- `String interactId`


## Methods

- `Transform get_targetPoint()`

- `String get_animationKey()`

- `LeftOrRight get_leftOrRight()`

- `Void set_leftOrRight(LeftOrRight)`

- `Boolean get_specifyDir()`

- `Vector2 get_interactTime()`

- `Void QueryEntryPoints(Action`2)`

- `Void SetEntryPoints(Func`3)`

- `String get_interactId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AttachPoint : IAttachPoint
{
	private Transform _targetPoint; // 0x10
	private String _animationKey; // 0x18
	private LeftOrRight _leftOrRight; // 0x20
	private Boolean _specifyDir; // 0x24
	private Vector2 _interactTime; // 0x28
	private String _interactId; // 0x30
	private IntPair[] _entries; // 0x38

	public Transform targetPoint { get; }
	public String animationKey { get; }
	public LeftOrRight leftOrRight { get; set; }
	public Boolean specifyDir { get; }
	public Vector2 interactTime { get; }
	public String interactId { get; }

	// RVA: 0x37cf040 VA: 0x7595de7040
	public Transform get_targetPoint() { }
	// RVA: 0x37cf048 VA: 0x7595de7048
	public String get_animationKey() { }
	// RVA: 0x37cf050 VA: 0x7595de7050
	public LeftOrRight get_leftOrRight() { }
	// RVA: 0x37cf058 VA: 0x7595de7058
	public Void set_leftOrRight(LeftOrRight value) { }
	// RVA: 0x37cf060 VA: 0x7595de7060
	public Boolean get_specifyDir() { }
	// RVA: 0x37cf068 VA: 0x7595de7068
	public Vector2 get_interactTime() { }
	// RVA: 0x37cf070 VA: 0x7595de7070
	public Void QueryEntryPoints(Action`2 action) { }
	// RVA: 0x37ce4d0 VA: 0x7595de64d0
	public Void SetEntryPoints(Func`3 action) { }
	// RVA: 0x37cf124 VA: 0x7595de7124
	public String get_interactId() { }
	// RVA: 0x37cf12c VA: 0x7595de712c
	public Void .ctor() { }
}
```