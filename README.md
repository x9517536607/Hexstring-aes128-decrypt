# Hexstring-aes128-decrypt

//usage
NSString* message = @"your hex string!!";   
NSString *key = @"your key";
NSString *iv = @"your iv";

NSData *messageData = [self dataFromHexString:message];
NSLog(@"DECRYPTED >> %@", [self AES128Decrypt:messageData key:key iv:iv]);