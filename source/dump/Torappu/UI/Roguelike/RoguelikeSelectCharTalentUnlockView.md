# RoguelikeSelectCharTalentUnlockView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _detail`

- `Image _icon`


## Methods

- `Void InitText(TalentUnlockType, UnlockCondition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSelectCharTalentUnlockView : MonoBehaviour, IHotfixable
{
	private Text _detail; // 0x18
	private Image _icon; // 0x20
	private Sprite[] _unlockIcon; // 0x28
	private const Int32 NEW_ONE; // 0x0
	private const Int32 NEW_TWO; // 0x0
	private const Int32 UPDATE_ONE; // 0x0
	private const Int32 UPDATE_TWO; // 0x0
	private const Int32 LVL; // 0x0
	private static DelegateBridge __Hotfix0_InitText; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2acfb38 VA: 0x75950e7b38
	public Void InitText(TalentUnlockType unlockType, UnlockCondition unlockCondition) { }
	// RVA: 0x2acfe7c VA: 0x75950e7e7c
	public Void .ctor() { }
}
```