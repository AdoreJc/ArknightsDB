# ActMultiV3DifficultyIconView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject _trainingNode`

- `GameObject _ordinaryNode`

- `Text _ordinaryText`

- `GameObject _difficultyNode`

- `Text _difficultyText`

- `GameObject _extremelyNode`

- `Text _extremelyText`

- `UIScaler m_scaler`


## Methods

- `Void Render(ActMultiV3DifficultyIconViewModel)`

- `Void SetScale(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3DifficultyIconView : MonoBehaviour, IHotfixable
{
	private GameObject _trainingNode; // 0x18
	private GameObject _ordinaryNode; // 0x20
	private Text _ordinaryText; // 0x28
	private GameObject _difficultyNode; // 0x30
	private Text _difficultyText; // 0x38
	private GameObject _extremelyNode; // 0x40
	private Text _extremelyText; // 0x48
	private UIScaler m_scaler; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_SetScale; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30e368c VA: 0x75956fb68c
	public Void Render(ActMultiV3DifficultyIconViewModel model) { }
	// RVA: 0x30e38e4 VA: 0x75956fb8e4
	public Void SetScale(Single scale) { }
	// RVA: 0x30e3a20 VA: 0x75956fba20
	public Void .ctor() { }
}
```