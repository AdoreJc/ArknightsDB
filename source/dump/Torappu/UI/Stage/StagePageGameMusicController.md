# StagePageGameMusicController

**Namespace:** `Torappu.UI.Stage`


## Methods

- `Void UpdateChunk(Int64, String)`

- `Void ClearChunk(Int64)`

- `Void ClearAllChunks()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePageGameMusicController : IHotfixable
{
	private readonly Dictionary`2 m_chunks; // 0x10
	private static DelegateBridge __Hotfix0_UpdateChunk; // 0x0
	private static DelegateBridge __Hotfix0_ClearChunk; // 0x8
	private static DelegateBridge __Hotfix0_ClearAllChunks; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f60f90 VA: 0x7595578f90
	public Void UpdateChunk(Int64 instanceId, String musicId) { }
	// RVA: 0x2f610e4 VA: 0x75955790e4
	public Void ClearChunk(Int64 instanceId) { }
	// RVA: 0x2f611d0 VA: 0x75955791d0
	public Void ClearAllChunks() { }
	// RVA: 0x2f61338 VA: 0x7595579338
	public Void .ctor() { }
}
```