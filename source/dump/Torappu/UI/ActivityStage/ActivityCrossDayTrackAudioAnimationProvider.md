# ActivityCrossDayTrackAudioAnimationProvider

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `String _entryAnimTrackId`

- `ActivityStageComponent m_component`

- `ActivityStageController m_controller`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Boolean CanPlayAudio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class ActivityCrossDayTrackAudioAnimationProvider : MonoBehaviour, IAudioAnimationPlayerConditionProvider, IHotfixable
{
	private String _entryAnimTrackId; // 0x18
	private ActivityStageComponent m_component; // 0x20
	private ActivityStageController m_controller; // 0x28
	private Boolean m_inited; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_CanPlayAudio; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3093fe8 VA: 0x75956abfe8
	private Void _InitIfNot() { }
	// RVA: 0x30940f8 VA: 0x75956ac0f8
	public Boolean CanPlayAudio() { }
	// RVA: 0x309420c VA: 0x75956ac20c
	public Void .ctor() { }
}
```