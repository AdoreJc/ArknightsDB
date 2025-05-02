# RoguelikeTopicEndingGpView

**Namespace:** `Torappu.UI.RoguelikeTopic.Ending`


## Fields

- `Image _gpIcon`

- `Text _gpName`

- `Text _gpCount`

- `Single _tweenGpDur`

- `Tween m_gpTween`

- `Int32 m_tempGp`


## Methods

- `Void Flush(Model)`

- `Void _SetGP(Int32)`

- `Int32 _GetGP()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Ending
public class RoguelikeTopicEndingGpView : MonoBehaviour, IHotfixable
{
	private Image _gpIcon; // 0x18
	private Text _gpName; // 0x20
	private Text _gpCount; // 0x28
	private Single _tweenGpDur; // 0x30
	private Tween m_gpTween; // 0x38
	private Int32 m_tempGp; // 0x40
	private static DelegateBridge __Hotfix0_Flush; // 0x0
	private static DelegateBridge __Hotfix0__SetGP; // 0x8
	private static DelegateBridge __Hotfix0__GetGP; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x26dadc8 VA: 0x7594cf2dc8
	public Void Flush(Model model) { }
	// RVA: 0x26db2c4 VA: 0x7594cf32c4
	private Void _SetGP(Int32 v) { }
	// RVA: 0x26db3b0 VA: 0x7594cf33b0
	private Int32 _GetGP() { }
	// RVA: 0x26db418 VA: 0x7594cf3418
	public Void .ctor() { }
}
```