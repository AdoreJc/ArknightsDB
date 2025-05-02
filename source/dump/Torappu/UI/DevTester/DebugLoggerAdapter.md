# DebugLoggerAdapter

**Namespace:** `Torappu.UI.DevTester`


## Fields

- `GameObject _logItem`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DevTester
public class DebugLoggerAdapter : RecycleLoopScrollAdapter`2
{
	private GameObject _logItem; // 0x68
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x0
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29ba608 VA: 0x7594fd2608
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x29ba6c4 VA: 0x7594fd26c4
	protected override Void OnDataSourceChanged() { }
	// RVA: 0x29ba730 VA: 0x7594fd2730
	public override Void UpdateView(Int32 position, GameObject viewObj, LogItemViewHolder holder, Log viewModel) { }
	// RVA: 0x29ba9d4 VA: 0x7594fd29d4
	public Void .ctor() { }
}
```