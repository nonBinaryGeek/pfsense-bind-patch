--- a/usr/local/pkg/bind.inc 2024-05-07 03:25:55.667801000 -0400
+++ b/usr/local/pkg/bind.inc 2024-05-07 03:28:21.518008000 -0400
@@ -281,8 +281,8 @@
 
 logging {
 	channel custom {
-		syslog daemon;
-		print-time no;
+		file "/var/log/bind.log" versions 3 size 100m;
+		print-time yes;
 		print-severity yes;
 		print-category yes;
 		severity {$log_severity};
