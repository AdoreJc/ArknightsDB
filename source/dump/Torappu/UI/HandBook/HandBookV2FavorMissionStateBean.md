# HandBookV2FavorMissionStateBean

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2FavorMissionProperty _favorMissionProperty`


## Methods

- `Void RefreshData()`

- `Void RefreshRewardState()`

- `Void _RefreshData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2FavorMissionStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	private HandBookV2FavorMissionProperty _favorMissionProperty; // 0x18
	private Dictionary`2 m_forceId2CharDataListMap; // 0x20
	private Dictionary`2 m_forceId2FavorModelMap; // 0x28
	private List`1 m_cachedIdList; // 0x30
	private static DelegateBridge __Hotfix0_RefreshData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshRewardState; // 0x8
	private static DelegateBridge __Hotfix0__RefreshData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2ec9348 VA: 0x75954e1348
	public Void RefreshData() { }
	// RVA: 0x2ec949c VA: 0x75954e149c
	public Void RefreshRewardState() { }
	// RVA: 0x2ed9d20 VA: 0x75954f1d20
	private Void _RefreshData() { }
	// RVA: 0x2edaf98 VA: 0x75954f2f98
	public Void .ctor() { }
}
```