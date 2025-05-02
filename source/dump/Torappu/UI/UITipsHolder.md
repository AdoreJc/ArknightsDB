# UITipsHolder

**Namespace:** `Torappu.UI`


## Fields

- `Category _category`

- `Boolean _showOnStart`

- `Boolean m_isDirty`


## Methods

- `Void ResetCategory(Category)`

- `Void RefreshTips()`

- `Void ResetCandiates(List`1)`

- `Void _RefreshTips(Boolean, List`1)`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UITipsHolder : MonoBehaviour, IHotfixable
{
	protected Text[] _tipsText; // 0x18
	protected Category _category; // 0x20
	protected Boolean _showOnStart; // 0x24
	private Boolean m_isDirty; // 0x25
	private static DelegateBridge __Hotfix0_ResetCategory; // 0x0
	private static DelegateBridge __Hotfix0_RefreshTips; // 0x8
	private static DelegateBridge __Hotfix0_ResetCandiates; // 0x10
	private static DelegateBridge __Hotfix0__RefreshTips; // 0x18
	private static DelegateBridge __Hotfix0_Start; // 0x20
	private static DelegateBridge __Hotfix0_SetTips; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x21f3c80 VA: 0x759480bc80
	public Void ResetCategory(Category category) { }
	// RVA: 0x21f3db8 VA: 0x759480bdb8
	public Void RefreshTips() { }
	// RVA: 0x21f3e28 VA: 0x759480be28
	public Void ResetCandiates(List`1 candiates) { }
	// RVA: 0x21f3d08 VA: 0x759480bd08
	private Void _RefreshTips(Boolean force, List`1 candiates) { }
	// RVA: 0x21f3eac VA: 0x759480beac
	private Void Start() { }
	// RVA: 0x21f3f30 VA: 0x759480bf30
	protected virtual Void SetTips(List`1 candiates) { }
	// RVA: 0x21f40f8 VA: 0x759480c0f8
	public Void .ctor() { }
}
```