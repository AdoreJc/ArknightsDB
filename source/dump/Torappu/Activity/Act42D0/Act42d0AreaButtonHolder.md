# Act42d0AreaButtonHolder

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Transform _buttonContainer`

- `Act42d0AreaButton _btnPrefab`

- `String _areaId`

- `Act42d0AreaButton m_cachedBtn`

- `Boolean m_isInited`

- `Act42d0AreaViewModel m_viewModel`


## Properties

- `String areaId`


## Methods

- `Void Render(Act42d0AreaViewModel, Boolean, NewestProgress, Boolean)`

- `String get_areaId()`

- `Void _InitIfNot()`

- `Boolean TryRegisterAreaGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42d0AreaButtonHolder : MonoBehaviour, IHotfixable
{
	private Transform _buttonContainer; // 0x18
	private Act42d0AreaButton _btnPrefab; // 0x20
	private String _areaId; // 0x28
	private Act42d0AreaButton m_cachedBtn; // 0x30
	private Boolean m_isInited; // 0x38
	private Act42d0AreaViewModel m_viewModel; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_get_areaId; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_TryRegisterAreaGo; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String areaId { get; }

	// RVA: 0x3217888 VA: 0x759582f888
	public Void Render(Act42d0AreaViewModel viewModel, Boolean isSelected, NewestProgress progressInfo, Boolean showStatusChanged) { }
	// RVA: 0x3217b10 VA: 0x759582fb10
	public String get_areaId() { }
	// RVA: 0x3217958 VA: 0x759582f958
	private Void _InitIfNot() { }
	// RVA: 0x3217b78 VA: 0x759582fb78
	public Boolean TryRegisterAreaGo() { }
	// RVA: 0x3217c94 VA: 0x759582fc94
	public Void .ctor() { }
}
```