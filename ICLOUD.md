##iCloud同步规则

*  Wingy 的 iCloud 同步功能自动开启，只需要保证系统中开启了iCloud Drive
*  iCloud Drive “WingyConfig”目录下所有“.conf”格式的文件将被同步到Wingy App，文件名作为配置备注
*  Wingy app 的所有自定义配置自动保存到iCloud的“WingyConfig”目录，以“备注.conf”文件名保存
*  Wingy app 和 iCloud Drive中如果出现同名配置，最后更新的将覆盖较早更新的配置
*  iCloud Drive中删除配置不会同步删除 Wingy app 的配置（删除配置只能通过Wingy app 进行）
*  Wingy app 删除配置会同步删除iCloud Drive中同名的配置