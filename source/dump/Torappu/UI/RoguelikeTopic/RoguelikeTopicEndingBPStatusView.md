# RoguelikeTopicEndingBPStatusView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Text _bpLevel`

- `Scrollbar _bpPrg`

- `Text _bpPrgCount`

- `GameObject _maxTag`

- `Single _prgAnimDur`

- `Single _waitForNext`

- `Color _textColor`

- `String m_textColor`

- `Int32 m_tweenBp`

- `Int32 m_tweenMaxBp`


## Methods

- `Void Flush(String, Int32, Int32)`

- `IEnumerator TweenToTarget(String, Int32, Int32)`

- `Int32 _GetBp()`

- `Void _SetBp(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicEndingBPStatusView : MonoBehaviour, IHotfixable
{
	private Text _bpLevel; // 0x18
	private Scrollbar _bpPrg; // 0x20
	private Text _bpPrgCount; // 0x28
	private GameObject _maxTag; // 0x30
	private Single _prgAnimDur; // 0x38
	private Single _waitForNext; // 0x3c
	private Color _textColor; // 0x40
	private String m_textColor; // 0x50
	private Int32 m_tweenBp; // 0x58
	private Int32 m_tweenMaxBp; // 0x5c
	private static DelegateBridge __Hotfix0_Flush; // 0x0
	private static DelegateBridge __Hotfix0_TweenToTarget; // 0x8
	private static DelegateBridge __Hotfix0__GetBp; // 0x10
	private static DelegateBridge __Hotfix0__SetBp; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x264f7e4 VA: 0x7594c677e4
	public Void Flush(String topicId, Int32 bpFrom, Int32 bpTo) { }
	// RVA: 0x264f898 VA: 0x7594c67898
	public IEnumerator TweenToTarget(String topicId, Int32 srcBp, Int32 destBp) { }
	// RVA: 0x264f9b4 VA: 0x7594c679b4
	private Int32 _GetBp() { }
	// RVA: 0x264fa1c VA: 0x7594c67a1c
	private Void _SetBp(Int32 v) { }
	// RVA: 0x264fb64 VA: 0x7594c67b64
	public Void .ctor() { }
}
```