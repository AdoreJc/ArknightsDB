# ZoneRecordStateBean

**Namespace:** `Torappu.UI.Stage`


## Fields

- `ZoneRecordViewProperty property`

- `ZoneRecordGroupData m_cachedGroupData`


## Methods

- `Void LoadData(String)`

- `Void RefreshData()`

- `Void OnContentClick(String)`

- `Void EnsureLatestPageIdx()`

- `Void OnNoteCoverClick()`

- `Void OnNextNote()`

- `Void OnPrevNote()`

- `Void _JumpToRecordPageByIdx(Int32)`

- `Int32 GetLatestRocordIdx()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordStateBean : IStateBean, IHotfixable, IDataBindWrapper
{
	public ZoneRecordViewProperty property; // 0x10
	private ZoneRecordGroupData m_cachedGroupData; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge __Hotfix0_OnContentClick; // 0x10
	private static DelegateBridge __Hotfix0_EnsureLatestPageIdx; // 0x18
	private static DelegateBridge __Hotfix0_OnNoteCoverClick; // 0x20
	private static DelegateBridge __Hotfix0_OnNextNote; // 0x28
	private static DelegateBridge __Hotfix0_OnPrevNote; // 0x30
	private static DelegateBridge __Hotfix0__JumpToRecordPageByIdx; // 0x38
	private static DelegateBridge __Hotfix0_GetLatestRocordIdx; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2fc8fc4 VA: 0x75955e0fc4
	public Void LoadData(String zoneId) { }
	// RVA: 0x2fc9190 VA: 0x75955e1190
	public Void RefreshData() { }
	// RVA: 0x2fc9254 VA: 0x75955e1254
	public Void OnContentClick(String recordId) { }
	// RVA: 0x2fc9568 VA: 0x75955e1568
	public Void EnsureLatestPageIdx() { }
	// RVA: 0x2fc974c VA: 0x75955e174c
	public Void OnNoteCoverClick() { }
	// RVA: 0x2fc97d0 VA: 0x75955e17d0
	public Void OnNextNote() { }
	// RVA: 0x2fc98ac VA: 0x75955e18ac
	public Void OnPrevNote() { }
	// RVA: 0x2fc93c4 VA: 0x75955e13c4
	private Void _JumpToRecordPageByIdx(Int32 idx) { }
	// RVA: 0x2fc961c VA: 0x75955e161c
	public Int32 GetLatestRocordIdx() { }
	// RVA: 0x2fc99f4 VA: 0x75955e19f4
	public Void .ctor() { }
}
```