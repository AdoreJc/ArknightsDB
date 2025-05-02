# ArchiveQuestTypeBtnView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _objectNew`

- `Text _textName`

- `TwoStateToggle _toggleIfLocked`

- `UIAnimationLocation _animLoop`

- `SandboxV2ArchiveQuestType _questType`


## Methods

- `Void Render(ArchiveQuestModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestTypeBtnView : MonoBehaviour, IHotfixable
{
	private GameObject _objectNew; // 0x18
	private Text _textName; // 0x20
	private TwoStateToggle _toggleIfLocked; // 0x28
	private UIAnimationLocation _animLoop; // 0x30
	public SandboxV2ArchiveQuestType _questType; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3071bb8 VA: 0x7595689bb8
	public Void Render(ArchiveQuestModel model) { }
	// RVA: 0x307792c VA: 0x759568f92c
	public Void .ctor() { }
}
```