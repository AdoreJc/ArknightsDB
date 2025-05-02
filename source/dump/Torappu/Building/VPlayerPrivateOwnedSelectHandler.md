# VPlayerPrivateOwnedSelectHandler

**Namespace:** `Torappu.Building`


## Fields

- `BuildingController m_controller`

- `VCharacter m_vchar`

- `Boolean m_isActive`


## Methods

- `Boolean IsActive()`

- `Void BindController(BuildingController)`

- `Void _UnbindEventAndClearCache()`

- `Void _OnObjectSelected(Object)`

- `Void Clear()`

- `Boolean CheckNeedActiveWithoutController()`

- `Boolean _CheckPrivateChar()`

- `Void Tick(Single)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class VPlayerPrivateOwnedSelectHandler : IBuildingBindTools, IHotfixable, IDisposable
{
	private BuildingController m_controller; // 0x10
	private VCharacter m_vchar; // 0x18
	private Boolean m_isActive; // 0x20
	private static DelegateBridge __Hotfix0_IsActive; // 0x0
	private static DelegateBridge __Hotfix0_BindController; // 0x8
	private static DelegateBridge __Hotfix0__UnbindEventAndClearCache; // 0x10
	private static DelegateBridge __Hotfix0__OnObjectSelected; // 0x18
	private static DelegateBridge __Hotfix0_Clear; // 0x20
	private static DelegateBridge __Hotfix0_CheckNeedActiveWithoutController; // 0x28
	private static DelegateBridge __Hotfix0__CheckPrivateChar; // 0x30
	private static DelegateBridge __Hotfix0_Tick; // 0x38
	private static DelegateBridge __Hotfix0_Dispose; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3783550 VA: 0x7595d9b550
	public Boolean IsActive() { }
	// RVA: 0x37835b8 VA: 0x7595d9b5b8
	public Void BindController(BuildingController controller) { }
	// RVA: 0x37836dc VA: 0x7595d9b6dc
	private Void _UnbindEventAndClearCache() { }
	// RVA: 0x378382c VA: 0x7595d9b82c
	private Void _OnObjectSelected(Object obj) { }
	// RVA: 0x3783944 VA: 0x7595d9b944
	public Void Clear() { }
	// RVA: 0x37839ac VA: 0x7595d9b9ac
	public Boolean CheckNeedActiveWithoutController() { }
	// RVA: 0x3783a14 VA: 0x7595d9ba14
	private Boolean _CheckPrivateChar() { }
	// RVA: 0x3783bec VA: 0x7595d9bbec
	public Void Tick(Single ts) { }
	// RVA: 0x3783c8c VA: 0x7595d9bc8c
	public Void Dispose() { }
	// RVA: 0x3783cf4 VA: 0x7595d9bcf4
	public Void .ctor() { }
}
```