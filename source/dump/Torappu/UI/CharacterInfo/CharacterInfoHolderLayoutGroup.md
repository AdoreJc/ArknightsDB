# CharacterInfoHolderLayoutGroup

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Single _spacing`

- `Single _topHeight`

- `Boolean m_lockFlag`


## Methods

- `Single ReturnTotalHeight()`

- `Single _CalcHeight(Int32, Int32)`

- `Void RefreshViewHeight(ViewObj, Single, Single, Single)`

- `Void RegisterViews(List`1)`

- `Void NotifyRebuild()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoHolderLayoutGroup : MonoBehaviour, IHotfixable
{
	private Single _spacing; // 0x18
	private Single _topHeight; // 0x1c
	public List`1 viewPool; // 0x20
	private Boolean m_lockFlag; // 0x28
	private static DelegateBridge __Hotfix0_ReturnTotalHeight; // 0x0
	private static DelegateBridge __Hotfix0__CalcHeight; // 0x8
	private static DelegateBridge __Hotfix0_RefreshViewHeight; // 0x10
	private static DelegateBridge __Hotfix0_RegisterViews; // 0x18
	private static DelegateBridge __Hotfix0_NotifyRebuild; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d80cb8 VA: 0x7595398cb8
	public Single ReturnTotalHeight() { }
	// RVA: 0x2d80d20 VA: 0x7595398d20
	private Single _CalcHeight(Int32 startIndex, Int32 endIndex) { }
	// RVA: 0x2d80db4 VA: 0x7595398db4
	public Void RefreshViewHeight(ViewObj view, Single startHeight, Single targetHeight, Single duration) { }
	// RVA: 0x2d80e5c VA: 0x7595398e5c
	public Void RegisterViews(List`1 viewLists) { }
	// RVA: 0x2d80ed4 VA: 0x7595398ed4
	public Void NotifyRebuild() { }
	// RVA: 0x2d80f38 VA: 0x7595398f38
	public Void .ctor() { }
}
```