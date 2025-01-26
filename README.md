import React from 'react';

const CyberSecurityPortfolio = () => {
  const hackerArt = `         ___   ____
       /' --;^/ ,-_\\     \\ | /      
      / / --o\\ o-\\ \\\\   --(_)--  
     /-/-/|o|-|\\-\\\\|\\\\   / | \\   _____ _          _     _              _              
      '\`  \` |-|   \`\` '           / ____| |        (_)   | |            | |               
            |-|                 | |    | |__  _ __ _ ___| |_ ___  _ __ | |__   ___ _ __ 
            |-|O               | |    | '_ \\| '__| / __| __/ _ \\| '_ \\| '_ \\ / _ \\ '__|
            |-(\\,__           | |____| | | | |  | \\__ \\ || (_) | |_) | | | |  __/ |   
         ...|-|\\--,\\_....      \\_____|_| |_|_|  |_|___/\\__\\___/| .__/|_| |_|\\___|_|   
      ,;;;;;;;;;;;;;;;;;;;;;;;;,.                               | |                      
~~,;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;,   _    _ _   _         |_|           _             _       
                                        / \\  | | \\ | |   /\\   | | |         | |           | |      
                                       / _ \\ | |  \\| |  /  \\  | | |_ ___  __| |_ ___  ___| |_ ___ 
                                      / ___ \\| | |\\  | / /\\ \\ | | __/ _ \\/ __| __/ _ \\/ __| __/ __|
                                     /_/   \\_\\_|_| \\_|/_/  \\_\\_|_|\\__\\___/\\__/\\__\\___/\\___/\\__|___/
                                                                                        © 2025     `;

  return (
    <div className="min-h-screen bg-black text-green-400 font-mono p-4 text-xs">
      <div className="max-w-4xl mx-auto">
        <div className="bg-gray-900 border border-green-600 rounded p-4">
          <pre className="text-green-400 text-[0.6rem] leading-tight mb-4 overflow-x-auto whitespace-pre">{hackerArt}</pre>
          
          <div className="border-b border-green-600 pb-2 mb-4">
            <span className="text-green-300">root@christopher:~$</span> whoami
          </div>
          
          <div className="mb-4">
            <div className="text-lg font-bold">Christopher Androutsopoulos</div>
            <div>Cybersecurity Analyst | ServiceNow Consultant</div>
          </div>

          <div className="mb-4">
            <div className="text-green-300">root@christopher:~$ cat professional_experience.txt</div>
            <div className="pl-4">
              <div>ServiceNow | Consultant / Programmer (2 Years)</div>
              <ul className="list-disc pl-4">
                <li>Developed enterprise-level software solutions</li>
                <li>Implemented robust programming frameworks</li>
                <li>Collaborated with cross-functional technical teams</li>
              </ul>
            </div>
          </div>

          <div className="mb-4">
            <div className="text-green-300">root@christopher:~$ ls technical_skills</div>
            <div className="pl-4 flex flex-wrap gap-2">
              {['Python', 'Network Security', 'Threat Analysis', 'Incident Response', 
                'Linux', 'Wireshark', 'Security Tools'].map((skill) => (
                <span key={skill} className="bg-green-800 text-green-300 px-2 py-1 rounded text-xs">
                  {skill}
                </span>
              ))}
            </div>
          </div>

          <div className="mb-4">
            <div className="text-green-300">root@christopher:~$ show certifications</div>
            <div className="pl-4">
              {[
                'CompTIA Security+',
                'Google Cybersecurity Professional Certificate', 
                'CompTIA Network+'
              ].map((cert) => (
                <div key={cert} className="flex items-center">
                  <span className="mr-2">[*]</span>
                  <span>{cert}</span>
                  <span className="ml-2 bg-green-900 text-green-300 text-xs px-2 py-0.5 rounded">IN PROGRESS</span>
                </div>
              ))}
            </div>
          </div>

          <div className="mb-4">
            <div className="text-green-300">root@christopher:~$ cat career_objective.txt</div>
            <div className="pl-4 italic">
              Experienced ServiceNow consultant transitioning into cybersecurity. 
              Seeking to leverage technical expertise to protect organizations 
              from evolving digital threats.
            </div>
          </div>

          <div className="text-green-300">
            root@christopher:~$ contact
            <div className="pl-4">
              <span className="inline-block align-middle mr-2">📧</span> 
              christopher.androu@gmail.com
            </div>
          </div>
        </div>
      </div>
    </div>
  );
};

export default CyberSecurityPortfolio;
