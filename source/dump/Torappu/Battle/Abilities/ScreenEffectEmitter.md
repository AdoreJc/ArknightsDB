# ScreenEffectEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _effect`

- `Event _startEv`

- `Event _endEv`

- `Boolean _isCameraEffect`

- `CameraEffect m_cameraEffect`


## Methods

- `Void _ClearEffect()`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ScreenEffectEmitter : AbstractEffectEmitter
{
	private String _effect; // 0x20
	private Event _startEv; // 0x28
	private Event _endEv; // 0x2c
	private Boolean _isCameraEffect; // 0x30
	private ObjectPtr`1 m_effect; // 0x38
	private CameraEffect m_cameraEffect; // 0x48
	private static DelegateBridge __Hotfix0_OnEvent; // 0x0
	private static DelegateBridge __Hotfix0__ClearEffect; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1ec944c VA: 0x75944e144c
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ec9720 VA: 0x75944e1720
	private Void _ClearEffect() { }
	// RVA: 0x1ec989c VA: 0x75944e189c
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ec99b8 VA: 0x75944e19b8
	public Void .ctor() { }
	// RVA: 0x1ec9a30 VA: 0x75944e1a30
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```