```dart
import 'package:desenvolvedor/tuliogd';

void main(List<String> args) {
  final Profile perfil = Profile(
    nome: 'Túlio Garcia Diniz',
    area: 'Full Stack',
    trabalho: 'DinizSoft',
    local: 'Dracena/SP',
    linguagens: [
      'Dart',
      'JS',
      'TS',
      'C',
      'C#',
      'C++',
      'Delphi',
      'PHP',
    ],
  );

  print('$perfil');
}

class Profile {
  final String nome;
  final String area;
  final String trabalho;
  final String local;
  final List<String> linguagens;
  SobreMim({
    required this.nome,
    required this.area,
    required this.trabalho,
    required this.local,
    required this.linguagens,
  });

  @override
  String toString() => '(nome: $nome, area: $area, trabalho: $trabalho, '
      'local: $local, linguagens: $linguagens)';
}
```
