# TaskHandler

**Namespace:** ` `


## Fields

- `Boolean m_downloadFinishConsumed`

- `Action <onDownloadFinish>k__BackingField`

- `Boolean m_decompressFinishConsumed`

- `Action <onDecompressFinish>k__BackingField`

- `DownloadProgress <downloadProgress>k__BackingField`

- `Single <decompressProgress>k__BackingField`


## Properties

- `Action onDownloadFinish`

- `Action onDecompressFinish`

- `DownloadProgress downloadProgress`

- `Single decompressProgress`


## Methods

- `Void set_onError(Action`2)`

- `Action get_onDownloadFinish()`

- `Void set_onDownloadFinish(Action)`

- `Action get_onDecompressFinish()`

- `Void set_onDecompressFinish(Action)`

- `Void set_onDownloadPaused(Action`1)`

- `DownloadProgress get_downloadProgress()`

- `Void set_downloadProgress(DownloadProgress)`

- `Single get_decompressProgress()`

- `Void set_decompressProgress(Single)`

- `Boolean IsValid()`

- `Void Cancel()`

- `Void MgrOnly_ConsumeDownloadFinish()`

- `Void MgrOnly_ConsumeDecompressFinish()`

- `Void MgrOnly_InvokePausedCallback(PauseReason)`

- `Void MgrOnly_RaiseError(HGRetCodeType, Int32)`

- `Void MgrOnly_SetDownloadProg(DownloadProgress)`

- `Void MgrOnly_SetDecompressProg(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TaskHandler
{
	private Action`2 <onError>k__BackingField; // 0x10
	private Boolean m_downloadFinishConsumed; // 0x18
	private Action <onDownloadFinish>k__BackingField; // 0x20
	private Boolean m_decompressFinishConsumed; // 0x28
	private Action <onDecompressFinish>k__BackingField; // 0x30
	private Action`1 <onDownloadPaused>k__BackingField; // 0x38
	private DownloadProgress <downloadProgress>k__BackingField; // 0x40
	private Single <decompressProgress>k__BackingField; // 0x50

	private Action`2 onError { get; set; }
	private Action onDownloadFinish { get; set; }
	private Action onDecompressFinish { get; set; }
	private Action`1 onDownloadPaused { get; set; }
	public DownloadProgress downloadProgress { get; set; }
	public Single decompressProgress { get; set; }

	// RVA: 0x3751c44 VA: 0x7595d69c44
	private Action`2 get_onError() { }
	// RVA: 0x3751c4c VA: 0x7595d69c4c
	public Void set_onError(Action`2 value) { }
	// RVA: 0x3751c54 VA: 0x7595d69c54
	private Action get_onDownloadFinish() { }
	// RVA: 0x3751c5c VA: 0x7595d69c5c
	public Void set_onDownloadFinish(Action value) { }
	// RVA: 0x3751c64 VA: 0x7595d69c64
	private Action get_onDecompressFinish() { }
	// RVA: 0x3751c6c VA: 0x7595d69c6c
	public Void set_onDecompressFinish(Action value) { }
	// RVA: 0x3751c74 VA: 0x7595d69c74
	private Action`1 get_onDownloadPaused() { }
	// RVA: 0x3751c7c VA: 0x7595d69c7c
	public Void set_onDownloadPaused(Action`1 value) { }
	// RVA: 0x3751c84 VA: 0x7595d69c84
	public DownloadProgress get_downloadProgress() { }
	// RVA: 0x3751c90 VA: 0x7595d69c90
	private Void set_downloadProgress(DownloadProgress value) { }
	// RVA: 0x3751c98 VA: 0x7595d69c98
	public Single get_decompressProgress() { }
	// RVA: 0x3751ca0 VA: 0x7595d69ca0
	private Void set_decompressProgress(Single value) { }
	// RVA: 0x3751ca8 VA: 0x7595d69ca8
	public Boolean IsValid() { }
	// RVA: 0x3751cf4 VA: 0x7595d69cf4
	public Void Cancel() { }
	// RVA: 0x3751d2c VA: 0x7595d69d2c
	public Void MgrOnly_ConsumeDownloadFinish() { }
	// RVA: 0x3751d58 VA: 0x7595d69d58
	public Void MgrOnly_ConsumeDecompressFinish() { }
	// RVA: 0x3751d84 VA: 0x7595d69d84
	public Void MgrOnly_InvokePausedCallback(PauseReason reason) { }
	// RVA: 0x3751da0 VA: 0x7595d69da0
	public Void MgrOnly_RaiseError(HGRetCodeType codeType, Int32 errorCode) { }
	// RVA: 0x3751dbc VA: 0x7595d69dbc
	public Void MgrOnly_SetDownloadProg(DownloadProgress value) { }
	// RVA: 0x3751dc4 VA: 0x7595d69dc4
	public Void MgrOnly_SetDecompressProg(Single value) { }
	// RVA: 0x37509d4 VA: 0x7595d689d4
	public Void .ctor() { }
}
```