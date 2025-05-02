# RoguelikeDisasterNotify

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _disasterIcon`

- `Text _txtDisasterName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDisasterNotify : RoguelikeAnimNotify
{
	private Image _disasterIcon; // 0x30
	private Text _txtDisasterName; // 0x38
	private GameObject[] _levelLines; // 0x40
	private static DelegateBridge __Hotfix0_get_notifyType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override RoguelikeCustomNotifyType notifyType { get; }

	// RVA: 0x29fb66c VA: 0x759501366c
	public override RoguelikeCustomNotifyType get_notifyType() { }
	// RVA: 0x29fb6d4 VA: 0x75950136d4
	protected override Void Render(ValueBundle options) { }
	// RVA: 0x29fb848 VA: 0x7595013848
	public Void .ctor() { }
}
```