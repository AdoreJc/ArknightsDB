# ActVecBreakOffenseEntryStatusView

**Namespace:** `Torappu.Activity.ActVecBreak`


## Fields

- `Text _curLevelText`

- `Text _totalLevelText`

- `Text _progressText`


## Methods

- `Void SetViewActive(Boolean)`

- `Void TrySetProgress(Int32, Int32)`

- `Void TrySetZoneName(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActVecBreak
public class ActVecBreakOffenseEntryStatusView : MonoBehaviour, IHotfixable
{
	private Text _curLevelText; // 0x18
	private Text _totalLevelText; // 0x20
	private Text _progressText; // 0x28
	private static DelegateBridge __Hotfix0_SetViewActive; // 0x0
	private static DelegateBridge __Hotfix0_TrySetProgress; // 0x8
	private static DelegateBridge __Hotfix0_TrySetZoneName; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30d76e0 VA: 0x75956ef6e0
	public Void SetViewActive(Boolean isActive) { }
	// RVA: 0x30d776c VA: 0x75956ef76c
	public Void TrySetProgress(Int32 curLevel, Int32 totalLevel) { }
	// RVA: 0x30d78fc VA: 0x75956ef8fc
	public Void TrySetZoneName(String zoneName) { }
	// RVA: 0x30d7a18 VA: 0x75956efa18
	public Void .ctor() { }
}
```