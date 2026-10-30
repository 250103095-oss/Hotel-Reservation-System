Hotel Reservation System
Console app for booking hotel rooms (CSS 217, assignment option C).

Team: Aida Akmurat, Bagdat Atabek, Erasyl Kurmanbek

How to run
You need JDK 17 or newer.

./run.sh            start (Windows: run.bat)
./run.sh --reset    start with the sample data again
./test.sh           run the tests (Windows: test.bat)
Logins: admin/admin123, aida/aida123, bagdat/bagdat123 Test card: 4242 4242 4242 4242, expiry 12/30, CVV 123

Structure
src/hotel – source code
test/hotel – tests
database/seed – sample data
docs – documentation and diagrams
Design patterns: Strategy (pricing), Decorator (extras), Adapter (payment). Details are in Documentation.pdf.
