# http:// в приложении блокируется

iOS по умолчанию разрешает только https (App Transport Security). Для разработки в Info.plist: `NSAppTransportSecurity` → `NSAllowsLocalNetworking` = YES — это разрешает http для локальных адресов и не отключает защиту для интернета.
