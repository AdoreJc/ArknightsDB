# CharmDropStageItem

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Image _btnImage`

- `Text _stageName`

- `Sprite _validSprite`

- `Color _validClr`

- `Sprite _invalidSprite`

- `Color _invalidClr`

- `StageData m_stage`

- `Boolean m_unlock`

- `Boolean m_timeout`


## Methods

- `Void Flush(String)`

- `Void SetVisible(Boolean)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class CharmDropStageItem : MonoBehaviour, IHotfixable
{
	private Image _btnImage; // 0x18
	private Text _stageName; // 0x20
	private Sprite _validSprite; // 0x28
	private Color _validClr; // 0x30
	private Sprite _invalidSprite; // 0x40
	private Color _invalidClr; // 0x48
	private StageData m_stage; // 0x58
	private Boolean m_unlock; // 0x60
	private Boolean m_timeout; // 0x61
	private static DelegateBridge __Hotfix0_Flush; // 0x0
	private static DelegateBridge __Hotfix0_SetVisible; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x345146c VA: 0x7595a6946c
	public Void Flush(String stageID) { }
	// RVA: 0x34513e0 VA: 0x7595a693e0
	public Void SetVisible(Boolean v) { }
	// RVA: 0x345166c VA: 0x7595a6966c
	public Void EventOnClick() { }
	// RVA: 0x3451784 VA: 0x7595a69784
	public Void .ctor() { }
}
```