# DownloadHandlerFile

**Namespace:** `Torappu.Network`


## Fields

- `String m_targetFilePath`

- `FileStream m_fileStream`

- `FileMode m_fileMode`

- `Boolean m_isClosed`

- `Boolean m_isError`


## Properties

- `Boolean isError`


## Methods

- `Boolean get_isError()`

- `Void Close()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Network
public class DownloadHandlerFile : DownloadHandlerScript
{
	private String m_targetFilePath; // 0x18
	private FileStream m_fileStream; // 0x20
	private FileMode m_fileMode; // 0x28
	private Boolean m_isClosed; // 0x2c
	private Boolean m_isError; // 0x2d

	public Boolean isError { get; }

	// RVA: 0x67ac07c VA: 0x7598dc407c
	public Void .ctor(String targetFilePath, FileMode fileMode) { }
	// RVA: 0x67ac0fc VA: 0x7598dc40fc
	public Boolean get_isError() { }
	// RVA: 0x67ac1bc VA: 0x7598dc41bc
	protected override Boolean ReceiveData(Byte[] data, Int32 dataLength) { }
	// RVA: 0x67ac3e8 VA: 0x7598dc43e8
	protected override Void CompleteContent() { }
	// RVA: 0x67ac4c4 VA: 0x7598dc44c4
	public Void Close() { }
}
```