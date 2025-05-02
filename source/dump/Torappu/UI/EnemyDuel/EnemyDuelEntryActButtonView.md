# EnemyDuelEntryActButtonView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `GameObject _panelLock`

- `GameObject _panelOnEnd`

- `GameObject _hotspot`

- `UnityEvent _clickEvent`

- `EnemyDuelEntryViewModel m_cachedModel`


## Methods

- `Void Render(EnemyDuelEntryViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEntryActButtonView : MonoBehaviour, IHotfixable
{
	private GameObject _panelLock; // 0x18
	private GameObject _panelOnEnd; // 0x20
	private GameObject _hotspot; // 0x28
	private UnityEvent _clickEvent; // 0x30
	private EnemyDuelEntryViewModel m_cachedModel; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x294b0d0 VA: 0x7594f630d0
	public Void Render(EnemyDuelEntryViewModel viewModel) { }
	// RVA: 0x294b1bc VA: 0x7594f631bc
	public Void OnClick() { }
	// RVA: 0x294b24c VA: 0x7594f6324c
	public Void .ctor() { }
}
```