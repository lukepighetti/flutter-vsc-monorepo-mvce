If you open the project directory in VSC `my_test/test/widget_test.dart` has problems with `import 'package:flutter_test/flutter_test.dart';`, either saying the package doesn't exist, or that the functions contained within are not defined.

If you open `my_test` in VSC everything works properly.

I discorvered this when trying to install Flutter inside a monorepo alongside a project folder for Firebase Functions and a Node.js service
