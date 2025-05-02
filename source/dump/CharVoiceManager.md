# CharVoiceManager

**Namespace:** ` `


## Fields

- `State m_state`

- `Single m_playTime`

- `Param m_param`


## Methods

- `Void Init(Single, Param)`

- `Void Update()`

- `Void Trigger()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CharVoiceManager : IHotfixable
{
	private State m_state; // 0x10
	private Single m_playTime; // 0x14
	private Param m_param; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_Trigger; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2116298 VA: 0x759472e298
	public Void Init(Single offset, Param param) { }
	// RVA: 0x2116364 VA: 0x759472e364
	public Void Update() { }
	// RVA: 0x21163f8 VA: 0x759472e3f8
	public Void Trigger() { }
	// RVA: 0x21164a0 VA: 0x759472e4a0
	public Void .ctor() { }
}
```